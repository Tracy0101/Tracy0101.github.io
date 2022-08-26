# Difference between Prefix(++i) and Postfix(i++)
<br><br/>
## Prefix  ++i
1.increment first<br><br/>
2.return new,incremented value
<br><br/>
### example 1
```javascript
let i=0;
console.log(++i);//1
console.log(i); //1
```
### example 2
```javascript
let x=3,y=4;
y=++x
console.log(y)  //4
```
<br><br/>
## Postfix  i++
1.increment first<br><br/>
2.return the value before increment<br><br/>
3.the new incremented value can only be used in the **next line**
<br><br/>
### example 1
```javascript
let i=0;
console.log(i++);//0
console.log(i); //1
```
### example 2
```javascript
let x=3,y=4;
y=x++
console.log(y)  //3
```
<br><br/>
## Conclusion
### The key point is i++ return the old value and difference only showed next to other operators

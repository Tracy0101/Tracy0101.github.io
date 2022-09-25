# map的用法
<br><br/>
将同一个array里的元素同时作用一个function，并不改变original array，会创造一个新的array。
<br><br/>
如果arrya为空，则不会作用。
<br><br/>
<br><br/>
## 简单功能
- 找到它们的平方根

```javascript
const heynum = [1,4,9];

const newnum = heynum.map(math.sqrt) 
// [1,2,3]
```

## 更复杂的功能
- ✖️5 - 4

```javascript
const heynum = [1,4,9];

const newnum = heynum.map(Thefunction)

function Thefunction(num) {
  return num*5- 4
}
// [1,16,41]
```

<br><br/>
<br><br/>
## Note
执行的时候遇到了问题，显示“Unexpected token ILLEGAL”，于是我对照了自己的代码和参考网站上的不同之处，发现使用map功能的那一行结尾处并没有分号，这也许是一个值得注意的点。

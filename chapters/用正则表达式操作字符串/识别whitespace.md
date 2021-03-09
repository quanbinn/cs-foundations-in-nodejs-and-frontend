# 识别whitespace

## 打开实验文件

单击右方的[在线代码段Url网址](http://pythontutor.com/javascript.html#code=console.log%28decodeURIComponent%28'%2520'%29%29%0Aconsole.log%28decodeURIComponent%28'a%2520b'%29%29%0Aconsole.log%28decodeURIComponent%28'a%2520b%2520c'%29%29%0A%0Aconsole.log%28encodeURIComponent%28'%20'%29%29%0Aconsole.log%28encodeURIComponent%28'a%20b'%29%29%0Aconsole.log%28encodeURIComponent%28'a%20b%20c'%29%29&curInstr=6&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D), 浏览器里会打开一个新的页面，里面有下面的代码段，如下图所示。

```javascript
console.log(decodeURIComponent('%20'))
console.log(decodeURIComponent('a%20b'))
console.log(decodeURIComponent('a%20b%20c'))

console.log(encodeURIComponent(' '))
console.log(encodeURIComponent('a b'))
console.log(encodeURIComponent('a b c'))
```

## Reference

1. [JavaScript decodeURIComponent() 函数](https://www.w3school.com.cn/jsref/jsref_decodeURIComponent.asp)
2. [JavaScript encodeURIComponent() 函数](https://www.w3school.com.cn/jsref/jsref_encodeURIComponent.asp)

# 提取url中的请求内容

## 打开实验文件

单击右方的[在线代码段Url网址](http://pythontutor.com/javascript.html#code=let%20str%3D%22http%3A//ddhuman.com/physicalLearning%22%3B%0Alet%20regex%20%3D%20/http%28s%29%3F%3A%5C/%5C/%28%5B%5Cw-%5D%2B%5C.%29%2B%5B%5Cw-%5D%2B%28%5C/%5B%5Cw-%20./%3F%25%26%3D%5D*%29%3F/g%3B%20%0A%0Aconst%20matchResult%20%3D%20str.match%28regex%29%3B%0A%0Aconsole.log%28'------',%20matchResult%29%3B%0A%0Aconsole.log%28matchResult.length%29%3B%0Aconsole.log%28typeof%20matchResult%29%3B%0A%0Aconsole.log%28matchResult%5B0%5D%29%3B%20%0Aconsole.log%28matchResult%5B0%5D.substring%282,matchResult%5B0%5D.length-2%29%29%3B%0A&curInstr=8&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D), 浏览器里会打开一个新的页面，里面有下面的代码段，如下图所示。

```javascript
let str="http://ddhuman.com/physicalLearning";
let regex = /http(s)?:\/\/([\w-]+\.)+[\w-]+(\/[\w- ./?%&=]*)?/g; 

const matchResult = str.match(regex);

console.log('------', matchResult);

console.log(matchResult.length);
console.log(typeof matchResult);

console.log(matchResult[0]); 
console.log(matchResult[0].substring(2,matchResult[0].length-2));
```



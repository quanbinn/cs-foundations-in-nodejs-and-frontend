# 匹配html标签然后获取其内容

## 打开实验文件

单击右方的[在线代码段Url网址](http://pythontutor.com/visualize.html#code=let%20str%3D%22%3Ch3%3E%E5%AE%9E%E9%AA%8C%E6%AD%A5%E9%AA%A4%EF%BC%9A%E5%88%86%E6%9E%90%E7%9B%B8%E9%82%BB%E6%95%B0%3C/h3%3E%22%3B%0Alet%20regex%20%3D%20/%5C%3Ch3%3E%28.*%29%3C%5C/h3%3E/g%3B%20%0A%0Aconst%20matchResult%20%3D%20str.match%28regex%29%3B%0A%0Aconsole.log%28'------',%20matchResult%29%3B%0A%0Aconsole.log%28matchResult.length%29%3B%0Aconsole.log%28typeof%20matchResult%29%3B%0A%0Aconsole.log%28matchResult%5B0%5D%29%3B%20%0Aconsole.log%28matchResult%5B0%5D.substring%284,matchResult%5B0%5D.length-5%29%29%3B&cumulative=false&heapPrimitives=nevernest&mode=edit&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D&textReferences=false), 浏览器里会打开一个新的页面，里面有下面的代码段，如下图所示。

```javascript
let str="<h3>实验步骤：分析相邻数</h3>";
let regex = /\<h3>(.*)<\/h3>/g; 

const matchResult = str.match(regex);

console.log('------', matchResult);

console.log(matchResult.length);
console.log(typeof matchResult);

console.log(matchResult[0]); 
console.log(matchResult[0].substring(4,matchResult[0].length-5));
```




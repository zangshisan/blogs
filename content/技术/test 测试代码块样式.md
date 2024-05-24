
```js
// 匿名函数
function () {}

// 应用场景
// 闭包·访问外部函数的变量
function add(x) {
  return function(y) {
    return x + y;
  };
}
var result = add(10)(20); // 30

// 回调函数·setTimeout函数接受一个回调函数作为参数
setTimeout(function() {
  console.log('Hello World!');
}, 1000);
```


```css
width:100%;
height:auto
```

1. 随意给一个无序，不重复的数组data，任意抽出n个，相加和为sum，也可能无解，写出该函数。

2. 节流函数怎么写

3. 手写bind函数

4. arguments

5. 事件循环,promise、setTimeout、async/await的执行顺序

6. 使用纯css实现自适应搜索框，至少两种方法

7. css画一个三角形 和 '>'

8. 跨域通信问题

9. 使用数组reduce方法实现数组map方法

10. 判断数组两种方法，非数组转数组

11. 原生实现ajax

12. 元素相对浏览器位置

13. 拖拽事件

14. 点击一个a标签，从事件角度，说明控制器输出起href值过程

15. 获取一个二叉树最大深度

16. amd 和 cmd 规范

17. 解析一个url，包括hash值

18. cookie安全设置

19. 有一个versions是一个项目的版本号列表，因多人维护，
    不规则var versions = ['1.45.0', '1.5', '6', '3.3.3.3.3.3'],要求从小到大排序，注意‘1.45’比‘1.5’大， 排序结果： ['1.5', '1.45.0', '3.3.3.3.3.3', '6']




20. lazyman（eat, sleep, go, rest）:链式调用
21. setCookie
22. async/await promise setTimeout顺序
```js
new Promise(function(resolve) {
    console.log("promise1");
    resolve();
}).then(function() {
    console.log("promise2");
});
async function async1() {
    console.log("async1 start");
    await async2();
    console.log("async1 end");
}

async function async2() {
    console.log("async2");
}

console.log("script start");

setTimeout(function() {
    console.log("setTimeout");
}, 0);

async1();



console.log("script end");
```
23. service worker
24. BFC
25. 两个相邻的DIV，设置z-index

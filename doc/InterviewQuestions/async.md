- [前端面试题及答案汇总-Async篇](#%E5%89%8D%E7%AB%AF%E9%9D%A2%E8%AF%95%E9%A2%98%E5%8F%8A%E7%AD%94%E6%A1%88%E6%B1%87%E6%80%BB)
  - [第 1 题：`setTimeout、Promise、Async/Await` 的区别？](#%E7%AC%AC-1-%E9%A2%98settimeoutpromiseasyncawait-%E7%9A%84%E5%8C%BA%E5%88%AB)
  - [第 2 题：`Async/Await` 如何通过同步的方式实现异步？](#%E7%AC%AC-2-%E9%A2%98asyncawait-%E5%A6%82%E4%BD%95%E9%80%9A%E8%BF%87%E5%90%8C%E6%AD%A5%E7%9A%84%E6%96%B9%E5%BC%8F%E5%AE%9E%E7%8E%B0%E5%BC%82%E6%AD%A5)
  - [第 3 题：`Promise` 构造函数是同步执行还是异步执行，那么 `then` 方法呢？](#%E7%AC%AC-3-%E9%A2%98promise%E6%9E%84%E9%80%A0%E5%87%BD%E6%95%B0%E6%98%AF%E5%90%8C%E6%AD%A5%E6%89%A7%E8%A1%8C%E8%BF%98%E6%98%AF%E5%BC%82%E6%AD%A5%E6%89%A7%E8%A1%8C%E9%82%A3%E4%B9%88then%E6%96%B9%E6%B3%95%E5%91%A2)
  - [第 4 题：异步笔试题？](#%E7%AC%AC-4-%E9%A2%98%E5%BC%82%E6%AD%A5%E7%AC%94%E8%AF%95%E9%A2%98)
  - [第 5 题：JS异步解决方案的发展历程以及优缺点？](#%E7%AC%AC-5-%E9%A2%98js%E5%BC%82%E6%AD%A5%E8%A7%A3%E5%86%B3%E6%96%B9%E6%A1%88%E7%9A%84%E5%8F%91%E5%B1%95%E5%8E%86%E7%A8%8B%E4%BB%A5%E5%8F%8A%E4%BC%98%E7%BC%BA%E7%82%B9)



  ## 前端面试题及答案汇总

### [总览](https://github.com/lotosv2010/front-end-summary/issues?q=is%3Aopen+is%3Aissue+label%3Ainterview+label%3AAsync)

### 第 1 题：setTimeout、Promise、Async/Await 的区别？

公司：

解析：[第 1 题](https://github.com/lotosv2010/front-end-summary/issues/17)

<br/>

### 第 2 题：Async/Await 如何通过同步的方式实现异步？

公司：头条、微医

解析：[第 2 题](https://github.com/lotosv2010/front-end-summary/issues/19)

<br/>

### 第 3 题：Promise构造函数是同步执行还是异步执行，那么then方法呢？

公司：微医

解析：[第 3 题](https://github.com/lotosv2010/front-end-summary/issues/21)

<br/>

### 第 4 题：异步笔试题？

> 请写出下面代码的运行结果
```javascript
async function async1() {
    console.log('async1 start');
    await async2();
    console.log('async1 end');
}
async function async2() {
    console.log('async2');
}
console.log('script start');
setTimeout(function() {
    console.log('setTimeout');
}, 0)
async1();
new Promise(function(resolve) {
    console.log('promise1');
    resolve();
}).then(function() {
    console.log('promise2');
});
console.log('script end');
```

公司：头条

解析：[第 4 题](https://github.com/lotosv2010/front-end-summary/issues/23)

<br/>

### 第 5 题：JS异步解决方案的发展历程以及优缺点？

公司：滴滴、挖财、微医、海康

解析：[第 5 题](https://github.com/lotosv2010/front-end-summary/issues/25)

<br/>

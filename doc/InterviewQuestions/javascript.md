- [前端面试题及答案汇总-JavaScript篇](#%E5%89%8D%E7%AB%AF%E9%9D%A2%E8%AF%95%E9%A2%98%E5%8F%8A%E7%AD%94%E6%A1%88%E6%B1%87%E6%80%BB)
  - [第 1 题：请列举判断数组的方法，请分别介绍它们之间的区别和优劣？](#%E7%AC%AC-1-%E9%A2%98%E8%AF%B7%E5%88%97%E4%B8%BE%E5%88%A4%E6%96%AD%E6%95%B0%E7%BB%84%E7%9A%84%E6%96%B9%E6%B3%95%E8%AF%B7%E5%88%86%E5%88%AB%E4%BB%8B%E7%BB%8D%E5%AE%83%E4%BB%AC%E4%B9%8B%E9%97%B4%E7%9A%84%E5%8C%BA%E5%88%AB%E5%92%8C%E4%BC%98%E5%8A%A3)
  - [第 2 题：['1', '2', '3'].map(parseInt) what & why？](#%E7%AC%AC-2-%E9%A2%981-2-3mapparseint-what--why)
  - [第 3 题：什么是防抖和节流？有什么区别？如何实现？](#%E7%AC%AC-3-%E9%A2%98%E4%BB%80%E4%B9%88%E6%98%AF%E9%98%B2%E6%8A%96%E5%92%8C%E8%8A%82%E6%B5%81%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB%E5%A6%82%E4%BD%95%E5%AE%9E%E7%8E%B0)
  - [第 4 题：深度优先遍历和广度优先遍历，如何实现？](#%E7%AC%AC-4-%E9%A2%98%E6%B7%B1%E5%BA%A6%E4%BC%98%E5%85%88%E9%81%8D%E5%8E%86%E5%92%8C%E5%B9%BF%E5%BA%A6%E4%BC%98%E5%85%88%E9%81%8D%E5%8E%86%E5%A6%82%E4%BD%95%E5%AE%9E%E7%8E%B0)
  - [第 5 题：请分别用深度优先思想和广度优先思想实现一个拷贝函数？](#%E7%AC%AC-5-%E9%A2%98%E8%AF%B7%E5%88%86%E5%88%AB%E7%94%A8%E6%B7%B1%E5%BA%A6%E4%BC%98%E5%85%88%E6%80%9D%E6%83%B3%E5%92%8C%E5%B9%BF%E5%BA%A6%E4%BC%98%E5%85%88%E6%80%9D%E6%83%B3%E5%AE%9E%E7%8E%B0%E4%B8%80%E4%B8%AA%E6%8B%B7%E8%B4%9D%E5%87%BD%E6%95%B0)
  - [第 6 题：如何实现一个 `new`？](#%E7%AC%AC-6-%E9%A2%98%E5%A6%82%E4%BD%95%E5%AE%9E%E7%8E%B0%E4%B8%80%E4%B8%AA-new)
  - [第 7 题：有以下 3 个判断数组的方法，请分别介绍它们之间的区别和优劣？](#%E7%AC%AC-7-%E9%A2%98%E6%9C%89%E4%BB%A5%E4%B8%8B-3-%E4%B8%AA%E5%88%A4%E6%96%AD%E6%95%B0%E7%BB%84%E7%9A%84%E6%96%B9%E6%B3%95%E8%AF%B7%E5%88%86%E5%88%AB%E4%BB%8B%E7%BB%8D%E5%AE%83%E4%BB%AC%E4%B9%8B%E9%97%B4%E7%9A%84%E5%8C%BA%E5%88%AB%E5%92%8C%E4%BC%98%E5%8A%A3)
  - [第 8 题：介绍下重绘和回流（Repaint & Reflow），以及如何进行优化？](#%E7%AC%AC-8-%E9%A2%98%E4%BB%8B%E7%BB%8D%E4%B8%8B%E9%87%8D%E7%BB%98%E5%92%8C%E5%9B%9E%E6%B5%81repaint--reflow%E4%BB%A5%E5%8F%8A%E5%A6%82%E4%BD%95%E8%BF%9B%E8%A1%8C%E4%BC%98%E5%8C%96)
  - [第 9 题：改造下面的代码，使之输出0 - 9，写出你能想到的所有解法？](#%E7%AC%AC-9-%E9%A2%98%E6%94%B9%E9%80%A0%E4%B8%8B%E9%9D%A2%E7%9A%84%E4%BB%A3%E7%A0%81%E4%BD%BF%E4%B9%8B%E8%BE%93%E5%87%BA0---9%E5%86%99%E5%87%BA%E4%BD%A0%E8%83%BD%E6%83%B3%E5%88%B0%E7%9A%84%E6%89%80%E6%9C%89%E8%A7%A3%E6%B3%95)
  - [第 10 题：cookie 和 token 都存放在 header 中，为什么不会劫持 token？](#%E7%AC%AC-10-%E9%A2%98cookie-%E5%92%8C-token-%E9%83%BD%E5%AD%98%E6%94%BE%E5%9C%A8-header-%E4%B8%AD%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%8D%E4%BC%9A%E5%8A%AB%E6%8C%81-token)
  - [第 11 题：下面的代码打印什么内容，为什么？](#%E7%AC%AC-11-%E9%A2%98%E4%B8%8B%E9%9D%A2%E7%9A%84%E4%BB%A3%E7%A0%81%E6%89%93%E5%8D%B0%E4%BB%80%E4%B9%88%E5%86%85%E5%AE%B9%E4%B8%BA%E4%BB%80%E4%B9%88)
  - [第 12 题：简单改造下面的代码，使之分别打印 10 和 20？](#%E7%AC%AC-12-%E9%A2%98%E7%AE%80%E5%8D%95%E6%94%B9%E9%80%A0%E4%B8%8B%E9%9D%A2%E7%9A%84%E4%BB%A3%E7%A0%81%E4%BD%BF%E4%B9%8B%E5%88%86%E5%88%AB%E6%89%93%E5%8D%B0-10-%E5%92%8C-20)
  - [第 13 题：使用迭代的方式实现 flatten 函数？](#%E7%AC%AC-13-%E9%A2%98%E4%BD%BF%E7%94%A8%E8%BF%AD%E4%BB%A3%E7%9A%84%E6%96%B9%E5%BC%8F%E5%AE%9E%E7%8E%B0-flatten-%E5%87%BD%E6%95%B0)
  - [第 14 题：下面代码中 a 在什么情况下会打印 1？](#%E7%AC%AC-14-%E9%A2%98%E4%B8%8B%E9%9D%A2%E4%BB%A3%E7%A0%81%E4%B8%AD-a-%E5%9C%A8%E4%BB%80%E4%B9%88%E6%83%85%E5%86%B5%E4%B8%8B%E4%BC%9A%E6%89%93%E5%8D%B0-1)
  - [第 15 题：浏览器缓存读取规则？](#%E7%AC%AC-15-%E9%A2%98%E6%B5%8F%E8%A7%88%E5%99%A8%E7%BC%93%E5%AD%98%E8%AF%BB%E5%8F%96%E8%A7%84%E5%88%99)
  - [第 16 题：实现一个 sleep 函数？](#%E7%AC%AC-16-%E9%A2%98%E5%AE%9E%E7%8E%B0%E4%B8%80%E4%B8%AA-sleep-%E5%87%BD%E6%95%B0)
  - [第 17 题：使用 sort() 对数组 [3, 15, 8, 29, 102, 22] 进行排序，输出结果？](#%E7%AC%AC-17-%E9%A2%98%E4%BD%BF%E7%94%A8-sort-%E5%AF%B9%E6%95%B0%E7%BB%84-3-15-8-29-102-22-%E8%BF%9B%E8%A1%8C%E6%8E%92%E5%BA%8F%E8%BE%93%E5%87%BA%E7%BB%93%E6%9E%9C)
  - [第 18 题：输出以下代码执行的结果并解释为什么？](#%E7%AC%AC-18-%E9%A2%98%E8%BE%93%E5%87%BA%E4%BB%A5%E4%B8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E7%9A%84%E7%BB%93%E6%9E%9C%E5%B9%B6%E8%A7%A3%E9%87%8A%E4%B8%BA%E4%BB%80%E4%B9%88)
  - [第 19 题：call 和 apply 的区别是什么，哪个性能更好一些？](#%E7%AC%AC-19-%E9%A2%98call-%E5%92%8C-apply-%E7%9A%84%E5%8C%BA%E5%88%AB%E6%98%AF%E4%BB%80%E4%B9%88%E5%93%AA%E4%B8%AA%E6%80%A7%E8%83%BD%E6%9B%B4%E5%A5%BD%E4%B8%80%E4%BA%9B)
  - [第 20 题：实现 (5).add(3).minus(2) 功能？](#%E7%AC%AC-20-%E9%A2%98%E5%AE%9E%E7%8E%B0-5add3minus2-%E5%8A%9F%E8%83%BD)




  ## 前端面试题及答案汇总

### [总览](https://github.com/lotosv2010/front-end-summary/issues?q=is%3Aopen+is%3Aissue+label%3Ainterview+label%3AJavaScript)

### 第 1 题：请列举判断数组的方法，请分别介绍它们之间的区别和优劣？

公司：

解析：[第 1 题](https://github.com/lotosv2010/front-end-summary/issues/3)

<br/>

### 第 2 题：['1', '2', '3'].map(parseInt) what & why？

公司：

解析：[第 2 题](https://github.com/lotosv2010/front-end-summary/issues/5)

<br/>

### 第 3 题：什么是防抖和节流？有什么区别？如何实现？

公司：

解析：[第 3 题](https://github.com/lotosv2010/front-end-summary/issues/9)

<br/>

### 第 4 题：深度优先遍历和广度优先遍历，如何实现？

公司：

解析：[第 4 题](https://github.com/lotosv2010/front-end-summary/issues/13)

<br/>

### 第 5 题：请分别用深度优先思想和广度优先思想实现一个拷贝函数？

公司：

解析：[第 5 题](https://github.com/lotosv2010/front-end-summary/issues/15)

<br/>

### 第 6 题：如何实现一个 `new`？

公司：

解析：[第 6 题](https://github.com/lotosv2010/front-end-summary/issues/41)

<br/>

### 第 7 题：有以下 3 个判断数组的方法，请分别介绍它们之间的区别和优劣？
> `Object.prototype.toString.call() 、 instanceof 以及 Array.isArray()`

公司：

解析：[第 7 题](https://github.com/lotosv2010/front-end-summary/issues/47)

<br/>

### 第 8 题：介绍下重绘和回流（Repaint & Reflow），以及如何进行优化？

公司：

解析：[第 8 题](https://github.com/lotosv2010/front-end-summary/issues/49)

<br/>

### 第 9 题：改造下面的代码，使之输出0 - 9，写出你能想到的所有解法？

```javascript
for (var i = 0; i< 10; i++){
	setTimeout(() => {
		console.log(i);
    }, 1000)
}
```

公司：

解析：[第 9 题](https://github.com/lotosv2010/front-end-summary/issues/57)

<br/>

### 第 10 题：cookie 和 token 都存放在 header 中，为什么不会劫持 token？

公司：

解析：[第 10 题](https://github.com/lotosv2010/front-end-summary/issues/61)

<br/>

### 第 11 题：下面的代码打印什么内容，为什么？

```javascript
var b = 10;
(function b(){
    b = 20;
    console.log(b); 
})();
```

公司：

解析：[第 11 题](https://github.com/lotosv2010/front-end-summary/issues/69)

<br/>

### 第 12 题：简单改造下面的代码，使之分别打印 10 和 20？

```javascript
var b = 10;
(function b(){
    b = 20;
    console.log(b); 
})();
```

公司：

解析：[第 12 题](https://github.com/lotosv2010/front-end-summary/issues/71)

<br/>

### 第 13 题：使用迭代的方式实现 flatten 函数？

公司：

解析：[第 13 题](https://github.com/lotosv2010/front-end-summary/issues/73)

<br/>

### 第 14 题：下面代码中 a 在什么情况下会打印 1？

```javascript
var a = ?;
if(a == 1 && a == 2 && a == 3){
 	console.log(1);
}
```

公司：京东

解析：[第 14 题](https://github.com/lotosv2010/front-end-summary/issues/75)

<br/>

### 第 15 题：浏览器缓存读取规则？

> 可以分成 Service Worker、Memory Cache、Disk Cache 和 Push Cache，那请求的时候 from memory cache 和 from disk cache 的依据是什么，哪些数据什么时候存放在 Memory Cache 和 Disk Cache中？

公司：

解析：[第 15 题](https://github.com/lotosv2010/front-end-summary/issues/77)

<br/>

### 第 16 题：实现一个 sleep 函数？

> 比如 sleep(1000) 意味着等待1000毫秒，可从 Promise、Generator、Async/Await 等角度实现

公司：

解析：[第 16 题](https://github.com/lotosv2010/front-end-summary/issues/87)

<br/>

### 第 17 题：使用 sort() 对数组 [3, 15, 8, 29, 102, 22] 进行排序，输出结果？

公司：

解析：[第 17 题](https://github.com/lotosv2010/front-end-summary/issues/89)

<br/>

### 第 18 题：输出以下代码执行的结果并解释为什么？

```javascript
var obj = {
    '2': 3,
    '3': 4,
    'length': 2,
    'splice': Array.prototype.splice,
    'push': Array.prototype.push
}
obj.push(1)
obj.push(2)
console.log(obj)
```

公司：

解析：[第 18 题](https://github.com/lotosv2010/front-end-summary/issues/91)

<br/>

### 第 19 题：call 和 apply 的区别是什么，哪个性能更好一些？

公司：

解析：[第 19 题](https://github.com/lotosv2010/front-end-summary/issues/95)

<br/>

### 第 20 题：实现 (5).add(3).minus(2) 功能？

```javascript
例： 5 + 3 - 2，结果为 6
```

公司：百度

解析：[第 20 题](https://github.com/lotosv2010/front-end-summary/issues/99)

<br/>



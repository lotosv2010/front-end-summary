- [前端知识点总结-JavaScript篇](#%E5%89%8D%E7%AB%AF%E7%9F%A5%E8%AF%86%E7%82%B9%E6%80%BB%E7%BB%93)
  - [第 1 点：BOM和DOM解释与分析。](#%E7%AC%AC-1-%E7%82%B9bom%E5%92%8Cdom%E8%A7%A3%E9%87%8A%E4%B8%8E%E5%88%86%E6%9E%90)
  - [第 2 点：call、apply、bind的理解。](#%E7%AC%AC-2-%E7%82%B9callapplybind%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 3 点：闭包的理解。](#%E7%AC%AC-3-%E7%82%B9%E9%97%AD%E5%8C%85%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 4 点：js数据类型的理解。](#%E7%AC%AC-4-%E7%82%B9js%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 5 点：js函数的理解。](#%E7%AC%AC-5-%E7%82%B9js%E5%87%BD%E6%95%B0%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 6 点：js数组和对象的理解。](#%E7%AC%AC-6-%E7%82%B9js%E6%95%B0%E7%BB%84%E5%92%8C%E5%AF%B9%E8%B1%A1%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 7 点：js时间与日期的理解。](#%E7%AC%AC-7-%E7%82%B9js%E6%97%B6%E9%97%B4%E4%B8%8E%E6%97%A5%E6%9C%9F%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 8 点：js正则表达式的理解。](#%E7%AC%AC-8-%E7%82%B9js%E6%AD%A3%E5%88%99%E8%A1%A8%E8%BE%BE%E5%BC%8F%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 9 点：js Function类型的理解。](#%E7%AC%AC-9-%E7%82%B9js-function%E7%B1%BB%E5%9E%8B%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 10 点：js变量、作用域及内存的理解。](#%E7%AC%AC-10-%E7%82%B9js%E5%8F%98%E9%87%8F%E4%BD%9C%E7%94%A8%E5%9F%9F%E5%8F%8A%E5%86%85%E5%AD%98%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 11 点：js基本包装类型的理解。](#%E7%AC%AC-11-%E7%82%B9js%E5%9F%BA%E6%9C%AC%E5%8C%85%E8%A3%85%E7%B1%BB%E5%9E%8B%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 12 点：js内置对象的理解。](#%E7%AC%AC-12-%E7%82%B9js%E5%86%85%E7%BD%AE%E5%AF%B9%E8%B1%A1%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 13 点：js面向对象与原型的理解。](#%E7%AC%AC-13-%E7%82%B9js%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E4%B8%8E%E5%8E%9F%E5%9E%8B%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 14 点：js匿名函数和闭包的理解。](#%E7%AC%AC-13-%E7%82%B9js%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E4%B8%8E%E5%8E%9F%E5%9E%8B%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 15 点：js BOM的理解。](#%E7%AC%AC-15-%E7%82%B9js-bom%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 16 点：js浏览器检测的理解。](#%E7%AC%AC-16-%E7%82%B9js%E6%B5%8F%E8%A7%88%E5%99%A8%E6%A3%80%E6%B5%8B%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 17 点：js DOM基础的理解。](#%E7%AC%AC-17-%E7%82%B9js-dom%E5%9F%BA%E7%A1%80%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 18 点：js DOM进阶的理解。](#%E7%AC%AC-18-%E7%82%B9js-dom%E8%BF%9B%E9%98%B6%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 19 点：js DOM操作表格及样式的理解。](#%E7%AC%AC-19-%E7%82%B9js-dom%E6%93%8D%E4%BD%9C%E8%A1%A8%E6%A0%BC%E5%8F%8A%E6%A0%B7%E5%BC%8F%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 20 点：js DOM元素尺寸和位置的理解。](#%E7%AC%AC-20-%E7%82%B9js-dom%E5%85%83%E7%B4%A0%E5%B0%BA%E5%AF%B8%E5%92%8C%E4%BD%8D%E7%BD%AE%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 21 点：js DOM动态加载脚本和样式的理解。](#%E7%AC%AC-21-%E7%82%B9js-dom%E5%8A%A8%E6%80%81%E5%8A%A0%E8%BD%BD%E8%84%9A%E6%9C%AC%E5%92%8C%E6%A0%B7%E5%BC%8F%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 22 点：js事件入门的理解。](#%E7%AC%AC-22-%E7%82%B9js%E4%BA%8B%E4%BB%B6%E5%85%A5%E9%97%A8%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 23 点：js事件对象的理解。](#%E7%AC%AC-23-%E7%82%B9js%E4%BA%8B%E4%BB%B6%E5%AF%B9%E8%B1%A1%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 24 点：js事件绑定及深入的理解。](#%E7%AC%AC-23-%E7%82%B9js%E4%BA%8B%E4%BB%B6%E5%AF%B9%E8%B1%A1%E7%9A%84%E7%90%86%E8%A7%A3)



  ## 前端知识点总结

### [总览](https://github.com/lotosv2010/front-end-summary/issues?q=is%3Aopen+is%3Aissue+label%3Asummary+label%3AJavaScript)

### 第 1 点：BOM和DOM解释与分析。

解析：[第 1 点](https://github.com/lotosv2010/front-end-summary/issues/2)

<br/>

### 第 2 点：call、apply、bind的理解。

解析：[第 2 点](https://github.com/lotosv2010/front-end-summary/issues/4)

<br/>

### 第 3 点：闭包的理解。

解析：[第 3 点](https://github.com/lotosv2010/front-end-summary/issues/6)

<br/>

### 第 4 点：js数据类型的理解。

解析：[第 4 点](https://github.com/lotosv2010/front-end-summary/issues/8)

<br/>

### 第 5 点：js函数的理解。

解析：[第 5 点](https://github.com/lotosv2010/front-end-summary/issues/10)

<br/>

### 第 6 点：js数组和对象的理解。

解析：[第 6 点](https://github.com/lotosv2010/front-end-summary/issues/12)

<br/>

### 第 7 点：js时间与日期的理解。

解析：[第 7 点](https://github.com/lotosv2010/front-end-summary/issues/14)

<br/>

### 第 8 点：js正则表达式的理解。

解析：[第 8 点](https://github.com/lotosv2010/front-end-summary/issues/16)

<br/>

### 第 9 点：js Function类型的理解。

解析：[第 9 点](https://github.com/lotosv2010/front-end-summary/issues/18)

<br/>

### 第 10 点：js变量、作用域及内存的理解。

解析：[第 10 点](https://github.com/lotosv2010/front-end-summary/issues/20)

<br/>

### 第 11 点：js基本包装类型的理解。

解析：[第 11 点](https://github.com/lotosv2010/front-end-summary/issues/22)

<br/>

### 第 12 点：js内置对象的理解。

解析：[第 12 点](https://github.com/lotosv2010/front-end-summary/issues/24)

<br/>

### 第 13 点：js面向对象与原型的理解。

解析：[第 13 点](https://github.com/lotosv2010/front-end-summary/issues/26)

<br/>

### 第 14 点：js匿名函数和闭包的理解。

解析：[第 14 点](https://github.com/lotosv2010/front-end-summary/issues/28)

<br/>

### 第 15 点：js BOM的理解。

解析：[第 15 点](https://github.com/lotosv2010/front-end-summary/issues/30)

<br/>

### 第 16 点：js浏览器检测的理解。

解析：[第 16 点](https://github.com/lotosv2010/front-end-summary/issues/32)

<br/>

### 第 17 点：js DOM基础的理解。

解析：[第 17 点](https://github.com/lotosv2010/front-end-summary/issues/34)

<br/>

### 第 18 点：js DOM进阶的理解。

解析：[第 18 点](https://github.com/lotosv2010/front-end-summary/issues/36)

<br/>

### 第 19 点：js DOM操作表格及样式的理解。

解析：[第 19 点](https://github.com/lotosv2010/front-end-summary/issues/38)

<br/>

### 第 20 点：js DOM元素尺寸和位置的理解。

解析：[第 20 点](https://github.com/lotosv2010/front-end-summary/issues/40)

<br/>

### 第 21 点：js DOM动态加载脚本和样式的理解。

解析：[第 21 点](https://github.com/lotosv2010/front-end-summary/issues/42)

<br/>

### 第 22 点：js事件入门的理解。

解析：[第 22 点](https://github.com/lotosv2010/front-end-summary/issues/44)

<br/>

### 第 23 点：js事件对象的理解。

解析：[第 23 点](https://github.com/lotosv2010/front-end-summary/issues/46)

<br/>

### 第 24 点：js事件绑定及深入的理解。

解析：[第 24 点](https://github.com/lotosv2010/front-end-summary/issues/48)

<br/>

# HTML



# Angular



# JS

## 1.bind、call、apply 的区别？

答案：

call 和 apply 其实是一样的，区别就在于传参时参数是一个一个传或者是以一个数组的方式来传。
call 和 apply 都是在调用时生效，改变调用者的 this 指向。

```javascript
let name = 'Jack'
const obj = {name: 'Tom'}
function sayHi() {console.log('Hi! ' + this.name)}

sayHi() // Hi! Jack
sayHi.call(obj) // Hi! Tom
```

bind 也是改变 this 指向，不过不是在调用时生效，而是返回一个新函数。

```javascript
const newFunc = sayHi.bind(obj)
newFunc() // Hi! Tom
```

## 2.对象的定义方式有哪些？

有两种，第一种是对象字面量的形式：

```javascript
var obj = {
    key:value
}
```

第二种就是构造函数的形式：

```javascript
var obj = new Object();
obj.key = value;
```

两者的区别在于，第一种方式可以同时添加多个键值对，而第二种方式需要一个一个的添加。

# CSS

# 算法

# 面试题

## 1.网页从输入网址到渲染完成经历了哪些过程？

## 2.ajax请求的过程

## 3.js的数组去重

## 4.js数组排序

## 5.js的原型和原型链

## 6.js实现继承的方法

## 7.s的基本数据类型

## 8.js有哪些内置对象

## 9.js操作数组的方法

## 10.什么是闭包，闭包的优缺点

## 11.阻止时间冒泡和默认事件

## 12.js中apply、call和bind的区别

## 13.如何解决跨域的问题

## 14.写一个闭包

## 15.创建对象的方法

## 16.HTTP中Get、Post、Put与Delete的区别

## 17.箭头函数和普通函数的区别

## 18.常用http的http方法有哪些?

## 19.GET和POST的区别

## 20.HTTP请求报文与响应报文格式

## 21.理解 async/await

## 22.怎样添加、移除、移动、复制、创建和查找节点？

## 23.谈谈垃圾回收机制方式及内存管理


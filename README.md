# miniMVVM
简单的mvvm 类似于vue.js 提供了单双向数据绑定和事件监听

## 开发目的

了解mvvm框架的基本实现，加深对框架和javascript语法的理解。

## 主要功能

提供了插值表达式{{}}、v-on v-model数据绑定、v-on事件绑定等相关功能

## MVVM框架

Model:数据 View:视图—与用户交互的桥梁 Viewmodel:行为-数据转换器

## 核心原理

* 基于Object.defineProporty(obj,prop,descriptor)实现对数据的get、set定义和代理
* 事件绑定:addEventlistener
* 观察者模式 
     定义Subject为主题对象 observer为观察者 subject可以addObserver、removeObserver、notify来操作观察者,observer在subscribeTo主题后，主题调用notify——observer实现update
     
   
![image](https://github.com/gty1998/img-storge/blob/master/Jietu20190317-154143%402x.jpg)
设置interval使age自增演示数据绑定

![image](https://github.com/gty1998/img-storge/blob/master/Jietu20190317-154157%402x.jpg)
onclick绑定alert事件演示

![image](https://github.com/gty1998/img-storge/blob/master/Jietu20190317-154230%402x.jpg)
input框数据使用双向绑定



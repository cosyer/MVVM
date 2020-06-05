## 原生 js 实现双向绑定

在我看来vue和react都是数据驱动视图，但是vue属于标准的mvvm模型，react是从组件化演变而来。

* 原理

> Object.defineProperty(obj,name,{get:function(),set:function()})

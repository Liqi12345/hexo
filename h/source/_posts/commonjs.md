---
title: commonjs
date: 2018-10-22 10:19:55
tags:commonjs规范
---

模块化的标准

背景： 因为js没有一个模块系统，所以commonjs规范主要是为了弥补js标准的缺陷

**模块引用**

```js
var math = require('math') 
//如果在node_modules目录里，可以不写路径，否则写相对或绝对路径
```

**模块定义**

```js
module 对象，代表当前模块自身
export 属性，module的属性，向外暴露访问的接口
```

**好处**

```js
每个模块都有自己的独立命名空间

定义模块简单，接口简洁

支持导入和导出功能，实现彼此依赖关系

```


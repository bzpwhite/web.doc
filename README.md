# 《Web.doc》
* ~~前端学习笔记~~
* 前端技术速成

### PART1
* [JS基础相关](./context/part1/jsStandard.md)
	* JS基础
	* JS语句
	* JS表达式
	* 数组的push方法
	* JS对象
	* 队列与堆栈
	* JSON对象
	* JS语法
	* console对象
	* 命令行 API
	* 正则表达式
	* Promise
		* 大白话讲解Promise
		* all的用法
		* Promise/A+规范
		* jquery中的Promise
* [ES6相关](./context/part1/es6.md)
	* 变量
		* Let & Var
		* 暂时性死区
		* 块级作用域
		* const命令
		* ...
	* 数组的扩展
	* 扩展运算符的应用
	* 对象的扩展
		* 属性名表达式
		* `__proto__`属性
		* super 关键字
		* Null 传导运算符
		* 属性的遍历
	* 对象的扩展运算符
		* 解构赋值
		* Symbol
		* 作为属性名的 Symbol
		* 实例：消除魔术字符串
	* Set & Map
		* Set
		* Map
	* Proxy
		* Proxy 实例的方法
		* get()
		* set()
	* Promise 的含义
	* Iterator（遍历器）的概念
		* Generator 函数
	* Generator 与协程
		* 协程与子例程的差异
		* 协程与普通线程的差异
		* 异步操作的同步化表达
		* 控制流管理
	* 类的实例对象
	* 装饰器
	* Module 的语法
	* Module 的加载实现
	* 读懂 ECMAScript 规格
* [DOM/BOM相关](./context/part1/dom.md)
	* DOM
		* Node对象
		* Document对象
		* 盒状模型相关属性
	* BOM
		* History 对象
		* Cookie
		* AJAX
* [webSocket](./context/part1/webSocket.md)
	* 接口
		* WebSocket
		* CloseEvent
		* MessageEvent
	* 流
	* 阻塞
	* 把非阻塞I/O作为头等大事：Node
	* 原生无阻塞：Go
	* 性能评测
* [Node.js](./context/part1/node.js.md)
	* Node基础
		* 异常处理
		* 回调函数
		* 命令行脚本
	* Buffer对象
	* Child Process模块
		* Shell
		* Forever
	* events模块
	* Express
		* 中间件
	* Koa
		* 中间件
		* 路由
		* context对象
		* 错误处理机制
		* cookie
		* Request对象
		* Response对象
		* CSRF攻击
	* CommonJS规范
		* CommonJS模块的特点如下
		* AMD规范与CommonJS规范的兼容性
		* 加载规则
	* MongoDB的应用
		* Mongoose
	* DNS模块
	* NPM模块
	* os模块
	* Stream接口
		* 可读数据流
		* 继承可读数据流接口
		* 可写数据流
		* pipe方法
		* 转换数据流
		* HTTP请求
* [前端高并发](./context/part1/js_highConcurrency.md)
	* 高并发下的数据安全
		* 悲观锁思路
		* FIFO队列思路
		* 乐观锁思路
	* 大规模网站架构的缓存机制和几何分形学
		* 前端Cache机制
		* Web负载均衡
		* MySQL数据库内部缓存使用
		* 异地部署（地理分布式）
* [前端测试](./context/part1/codeDetection.md)
	* ESLint
	* Karma
	* Nightwatch
	* E2E
	* Selenium/PhantomJS
	* 其它
* [其它](./context/part1/http.md)
	* HTTP
		* form-data
		* x-www-form-urlencoded
		* Cookie/Session
		* Filter拦截
		* Ping
		* DOS命令
	* package.json文件
	* JavaScript
		* 数据库操作
		* 事件驱动和非阻塞式设计
		* 异步编程
			* 回调函数
			* 事件监听
			* 发布/订阅
			* Promises对象
			* Generator
			* 异常处理

### PART2
* [面向对象](./context/part2/ObjectOriented.md)
	* 模块的放大模式
	* 包装对象实例的方法
		* Unicode
	* 函数的定义方式有三种
	* *接口模式*
* [函数式编程](./context/part2/FunctionlProgramming.md)
	* 高阶函数
	* 闭包
* [设计原则/模式](./context/part2/designDiscipline.md)
	* 设计原则
		* 单一职责原则
		* 开闭原则
		* 里氏替换原则
		* 依赖倒置原则
		* 接口隔离原则
		* 迪米特法则
		* *S.O.L.I.D 代表什么?*
	* 设计模式
		* 装饰器模式

### PART3
* [npm](./context/part3/npm.md)
	* 基础
	* 开发NPM
* [Webpack](./context/part3/webpack.md)
	* 入口(Entry)
	* 出口(Output)
	* Loader
	* 插件(Plugins)
	* 使用 Loader
	* 支持的模块类型
* [react](./context/part3/react.md)
	* 简介
	* JSX
	* 组件&Props
		* 函数定义/类定义组件
		* 组件渲染
	* State & 生命周期
	* 数据自顶向下流动
	* *框架*
* [网页模板引擎](./context/part3/HTMLModel.md)
* [Tools](./context/part3/plugin.md)
	* Grunt
	* Redux

### PART4
* [前端架构](./context/part4/webFramework.md)
	* MVC
	* MVP
	* MVVM
	* *B/S架构*
	* *C/S架构*
* [前端文档/工具链接](./context/part4/js_tool_link.md)
* [其它](./context/part4/JSnote.md)
	* 浏览器环境优化

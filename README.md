# HelloReact
[TOC]



## 1、React环境搭建

### （1）创建React app



安装create-react-app包

```shell
$ npm install create-react-app
```



使用create-react-app命令行工具

```shell
$ npx create-react-app my-app
```



运行react app

```shell
$ npm run start
```



编译react app生产环境版本

```shell
$ npm run build
```



部署react app生产环境版本

本地部署，如下

```shell
$ npm install -g serve
$ serve -s build
```



### （2）安装React Developer Tools浏览器插件

官方[^1]提供Chrome、Firefox和Edge浏览器的插件，其中Chrome插件下载地址是[这里](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)。

以Chrome插件为例，安装插件后，如果当前页面是React app的页面，`⎇ + ⌘ + i`打开Developer Tools，可以在Elements所在的Tab栏看到⚛️ Components和⚛️ Profiler两个Tab。

说明

> 如果当前页面不是React app的页面，则没有⚛️ Components和⚛️ Profiler两个Tab









## 2、React语法



React component类的constructor函数，必须调用super(props)

> In [JavaScript classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes), you need to always call `super` when defining the constructor of a subclass. All React component classes that have a `constructor` should start with a `super(props)` call.





## References

[^1]:https://reactjs.org/blog/2015/09/02/new-react-developer-tools.html#installation


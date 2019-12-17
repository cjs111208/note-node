# **Node.js**

## [介绍](##介绍)

## [版本](##版本)

### 	[查看下载版本](###查看下载版本)

## [配置node环境变量](##配置node的环境变量)





## **介绍**

基于 Chrome 的V8 JS 解析引擎之上，解放了Javascript的编程能力，为 Javascript 提供了 后端编程的能力；所以说，Node.js 是 一个让javascript进行后端编程的一个运行平台；

v8引擎: V8引擎是一个JavaScript引擎实现，最初由一些语言方面专家设计，后被谷歌收购，随后谷歌对其进行了开源。V8使用C++开发,js在v8引擎下运行媲美二进制的速度 

1.编译型语言 linux java c++ c#

2.解析性语言 js 

## **版本**

lts版（开发必用），稳定

![下载node](.\image\2267589-bb1555667d5355af.png)

### 查看下载版本

![1576567873118](C:\Users\ADMINI~1\AppData\Local\Temp\1576567873118.png)

使用  npm ls -g --depth 0  可以查看所有全局插件

## **配置node的环境变量**

在nodejs根目录下创建两个文件夹

node_cache

node_global

创建之后打开cmd，输入

npm config set prefix "文件路径\node_global"

npm config set cache "文件路径\node_cache"

![配置](.\image\1576568350717.png)


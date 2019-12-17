[Nodejs](https://github.com/cjs111208/note-node#%E4%BB%8B%E7%BB%8D)

 [介绍](https://github.com/cjs111208/note-node#%E7%89%88%E6%9C%AC)

 [版本](https://github.com/cjs111208/note-node#%E6%9F%A5%E7%9C%8B%E4%B8%8B%E8%BD%BD%E7%89%88%E6%9C%AC)

  [查看下载版本](https://github.com/cjs111208/note-node#%E6%9F%A5%E7%9C%8B%E4%B8%8B%E8%BD%BD%E7%89%88%E6%9C%AC)

 [配置node的环境变量](https://github.com/cjs111208/note-node#%E9%85%8D%E7%BD%AEnode%E7%9A%84%E7%8E%AF%E5%A2%83%E5%8F%98%E9%87%8F)



# Nodejs

## **介绍**

基于 Chrome 的V8 JS 解析引擎之上，解放了Javascript的编程能力，为 Javascript 提供了 后端编程的能力；所以说，Node.js 是 一个让javascript进行后端编程的一个运行平台；

v8引擎: V8引擎是一个JavaScript引擎实现，最初由一些语言方面专家设计，后被谷歌收购，随后谷歌对其进行了开源。V8使用C++开发,js在v8引擎下运行媲美二进制的速度 

1.编译型语言 linux java c++ c#

2.解析性语言 js 

## **版本**

lts版（开发必用），稳定

![下载node](https://github.com/cjs111208/note-node/blob/master/image/2267589-bb1555667d5355af.png)

### 查看下载版本

![1576567873118](https://github.com/cjs111208/note-node/blob/master/image/2267589-2c9ced41baca7c1e.png)

使用  npm ls -g --depth 0  可以查看所有全局插件

## **配置node的环境变量**

在nodejs根目录下创建两个文件夹

node_cache

node_global

创建之后打开cmd，输入

npm config set prefix "文件路径\node_global"

npm config set cache "文件路径\node_cache"

![配置](https://github.com/cjs111208/note-node/blob/master/image/1576568350717.png)


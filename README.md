前端工程化入门：VUE的实践
====

### 目的

> 本书记录的是我的团队在前端工程化的转变过程中，所学的知识。
> 我们团队的背景：对HTML、CSS、Javascript (ES5)都比较熟悉，做过多个前后端不分离的项目。
> 对前端开发进行转型，转成前后端分离模式。

本书的目的不是做一个全面的教材，只力求通过它能够快速的开始使用VUE做一些普通的项目。节省去网上浩瀚的信息中去搜寻自己需要部分的时间。
尤其对VUE的讲解部分，更是如此。更深入全面的了解建议参考VUE官方文档。

在我的技术生涯中，我一直遵守着这么一个学习原则： 

1. 快速入门
2. 进行实践
3. 在实践中发现问题、解决问题，继续学习
4. 经过几轮实践后，找时间系统的学习相关的技术及理论
5. 回到第2步，多次迭代

本书只讲解第一步的内容，目的依据这个教程能够快速的进入到第二步，能够编写/开发一些一般的软件。帮大家从纷纷繁杂的知识体系里挑出一些进入第二步必须的知识。


### 本书主要包含两部分内容

* 前端工程化的一个概述
* VUE的快速入门，编写一般项目用到的知识讲解


### 用到的代码

书中所有的代码，整理出来一个演示项目，在[sample-project目录下](./sample-project)。

### 版本

本书的讲解和例子都是基于VUE 3，其它版本可能略有不同。

| 项目 | 版本 |
|:------------:|:---------:|
NodeJS         | 10.12.0 |
npm            | 6.4.1 |
VUE            | 3.1.3 |
vue-router     | 3.0.1 |
vue-resource   | 1.5.1 |
sockjs         | 1.3.0 |
stompjs        | 2.3.3 |

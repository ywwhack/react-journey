# React 相关的优秀资源
以下列出的资源主要来自自己学习react过程中看过的觉的不错的文章、教程以及各种神坑的解决方案，也算是一个学习过程的记录。(ps:教程和文章有时候并没有严格区分，在这里我只是把需要花比较长时间研究的称作教程)

## React
### 教程
名称  |  简介
---- | ----
[reactjsprogram](http://www.reactjsprogram.com/) | 强烈建议英文好的童鞋去看看，第一部分是带着你从零构建一个github相关的小项目，讲了很多react重要的概念，作为入门和建立正确的react方法论很有用。该系列分react基础、es6/es7与react的结合、Redux+Immutable、react native和universal react，只有第一部分是免费的，其余都是付费的（相当贵）。

### 文章
名称  |  简介
---- | ----
[Presentational and Container Components](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0#.3tk94s6k0) | 介绍了react中Presentational和Container Components的概念和区别，以及使用场景

## Redux
### 教程
名称  | 简介
---- | ----
[Full-Stack Redux Tutorial](http://teropa.info/blog/2015/09/10/full-stack-redux-tutorial.html) | 这是一篇博客文章，内容相当的多，作者从零搭建了一个实时投票系统，从服务端到浏览器前端，介绍了如何使用[mocha](https://mochajs.org/),[chai](http://chaijs.com/)进行功能测试，如何使用[Immutable.js](https://github.com/facebook/immutable-js)，以及如何进行react组件的测试。作者在整篇文章中，一点点引入redux中的概念，深入浅出。还有一点非常有意思的是，作者在前后端分别建立了个redux。

## stackoverflow上的问答
问题  |  简介
---- | ----
[How to dispatch a Redux action with a timeout?](http://stackoverflow.com/questions/35411423/how-to-dispatch-a-redux-action-with-a-timeout/35415559#35415559) | 回答者是Redux的作者，阐述了如何在Redux中进行异步操作，什么情况下需要对异步操作进行封装，以及redux-thunk中间件的使用。
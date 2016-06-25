# React 相关的优秀资源
以下列出的资源主要来自自己学习react过程中看过的觉的不错的文章、教程以及各种神坑的解决方案，也算是一个学习过程的记录。(ps:教程和文章有时候并没有严格区分，在这里我只是把需要花比较长时间研究的称作教程)

## React
### 教程
名称  |  简介
---- | ----
[reactjsprogram](http://www.reactjsprogram.com/) | 强烈建议英文好的童鞋去看看，第一部分是带着你从零构建一个github相关的小项目，讲了很多react重要的概念，作为入门和建立正确的react方法论很有用。该系列分react基础、es6/es7与react的结合、Redux+Immutable、react native和universal react，只有第一部分是免费的，其余都是付费的（相当贵）。
[fullstackreact](https://www.fullstackreact.com/) | 整本书会涉及好几个项目的构建，由易到难。第一个项目是一个类似stackoverflow的投票系统，非常基础，没有es6，没有webpack，只是单纯的教你如何使用Component的思想开发应用。第二个应用展示了搭建react app的正确步骤，并在上一个应用的基础上加了服务端数据的获取。
[How to write your own Virtual DOM](https://medium.com/@deathmood/how-to-write-your-own-virtual-dom-ee74acc13060#.uqcirh1ic) | react造轮子系列，教你如何实现一个简单的类react的库，比直接看源码来深入了解react方便多了。

### 文章
名称  |  简介
---- | ----
[Presentational and Container Components](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0#.3tk94s6k0) | 介绍了react中Presentational和Container Components的概念和区别，以及使用场景
[React Components, Elements, and Instances](https://facebook.github.io/react/blog/2015/12/18/react-components-elements-and-instances.html) | 详细介绍了React中令人困惑的Component和Element的区别，以及React底层是如何将Component解析为DOM树的。
[初识React中的High Order Component](https://leozdgao.me/chushi-hoc/) | 介绍了react中的高阶组件，通俗易懂，顺带还提了下react-redux中的connect的实现。
[reactjs源码分析-上篇（首次渲染实现原理）](http://purplebamboo.github.io/2015/09/15/reactjs_source_analyze_part_one/) | 研究React源码的入门指南，非常赞，全篇围绕React的渲染方法render展开讲解，递进的引入Component,ReactElement,ReactClass，对之后的源码阅读很有帮助。
[Learning React Without Using React](https://medium.com/javascript-inside/learn-the-concepts-part-1-418952d968cb#.6e7z5tvgq) | 作者抛开react库本身，围绕react中的render方法,virtual DOM,Component,单向数据流动等概念，实现了一个todolist的例子，demo虽易，但是思想非常棒。

## Redux
### 教程
名称 | 简介
---- | ----
[Full-Stack Redux Tutorial](http://teropa.info/blog/2015/09/10/full-stack-redux-tutorial.html) | 这是一篇博客文章，内容相当的多，作者从零搭建了一个实时投票系统，从服务端到浏览器前端，介绍了如何使用[mocha](https://mochajs.org/),[chai](http://chaijs.com/)进行功能测试，如何使用[Immutable.js](https://github.com/facebook/immutable-js)，以及如何进行react组件的测试。作者在整篇文章中，一点点引入redux中的概念，深入浅出。还有一点非常有意思的是，作者在前后端分别建立了个redux。

### 文章
名称 | 简介
---- | ----
[so-youve-screwed-up-your-redux-store-or-why-redux-makes-refactoring-easy](https://blog.boldlisting.com/so-youve-screwed-up-your-redux-store-or-why-redux-makes-refactoring-easy-400e19606c71?utm_campaign=React%2BNewsletter&utm_medium=email&utm_source=React_Newsletter_32#.1po5f1k30) | 主要讲述了对reducers的几种改进方式来对redux进行重构。
[The Redux Journey](https://www.youtube.com/watch?v=uvAXVMwHJXU&feature=youtu.be) | Dan在react-europe 2016上关于redux一年发展过程的总结，并且示范了如何使用redux的优秀特性。


## 问答
问题  |  简介
---- | ----
[How to dispatch a Redux action with a timeout?](http://stackoverflow.com/questions/35411423/how-to-dispatch-a-redux-action-with-a-timeout/35415559#35415559) | 回答者是Redux的作者，阐述了如何在Redux中进行异步操作，什么情况下需要对异步操作进行封装，以及redux-thunk中间件的使用。
[Why is 'key' needed?](https://www.reddit.com/r/reactjs/comments/4mjdcf/why_cant_i_put_key_in_default_props_or_define_the/d3xwa6m) | 解释了为什么在一个React Elements数组中需要指定每个元素的key属性。 

## Newsletter
* [http://reactjsnewsletter.com/](http://reactjsnewsletter.com/)
* [http://newsletter.fullstackreact.com/](http://newsletter.fullstackreact.com/)
# React 相关的优秀资源
以下列出的资源主要来自自己学习react过程中看过的觉的不错的文章、教程，也算是一个学习过程的记录。

## React
### 教程
名称  |  简介
---- | ----
[fullstackreact](https://www.fullstackreact.com/) | 如果只看一个react教程，并且希望全面的了解其生态圈，这本书就够了。
[reactjsprogram](http://www.reactjsprogram.com/) | 有几个大的系列(redux/react native等)，其中react基础部分是免费的，内容对初学者来说很优质。


### 文章
名称  |  简介
---- | ----
[Presentational and Container Components](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0#.3tk94s6k0) | 介绍了react中Presentational和Container Components的概念和区别，以及使用场景
[React Components, Elements, and Instances](https://facebook.github.io/react/blog/2015/12/18/react-components-elements-and-instances.html) | 详细介绍了React中令人困惑的Component和Element的区别，以及React底层是如何将Component解析为DOM树的。
[Learning React Without Using React](https://medium.com/javascript-inside/learn-the-concepts-part-1-418952d968cb#.6e7z5tvgq) | 作者抛开react库本身，围绕react中的render方法,virtual DOM,Component,单向数据流动等概念，实现了一个todolist的例子，demo虽易，但是思想非常棒。
[React.js in patterns](http://krasimirtsonev.com/blog/article/react-js-in-design-patterns?utm_campaign=React%2BNewsletter&utm_medium=email&utm_source=React_Newsletter_38) | react的设计模式
[初识React中的High Order Component](https://leozdgao.me/chushi-hoc/) | 介绍了react中的高阶组件，通俗易懂，顺带还提了下react-redux中的connect的实现。
[React Higher Order Components in depth](https://medium.com/@franleplant/react-higher-order-components-in-depth-cf9032ee6c3e#.4twzbtufq) | 介绍了高阶组件(HOC)的两种实现方式，以及如何通过它来重用代码、操作WrappedComponent的props/state，render劫持等等。
[react-interview-questions](https://tylermcginnis.com/react-interview-questions/) | react相关的"面试题", 很有意思

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

## CSS Modules
### 文章
名称 | 简介
---- | ----
[What are CSS Modules? A visual introduction](http://andrewhfarmer.com/what-are-css-modules/) | 介绍了什么是css modules，以及它是如何解决css global问题的。
[CSS Modules by Example](http://andrewhfarmer.com/css-modules-by-example) | 7个例子涵盖了css modules在React开发中使用的场景。

## Webpack
### 文章
名称 | 简介
---- | ----
[Webpack中hash与chunkhash的区别，以及js与css的hash指纹解耦方案](http://www.cnblogs.com/ihardcoder/p/5623411.html) | 比较深入的介绍了hash和chunkhash的一些东西
[Progressive loading for modern web applications via code splitting](https://medium.com/@lavrton/progressive-loading-for-modern-web-applications-via-code-splitting-fb43999735c6#.yi8ev5c95) | 介绍了如何使用require.ensure来实现code-split，同时实现延迟加载。
### 教程
名称 | 简介
---- | ----
[http://survivejs.com/webpack/introduction/](http://survivejs.com/webpack/introduction/) | 目前看过最全面，也是唯一一本专门介绍webpack的书（webpack是个巨坑＝＝）。
[Webpack Deep Dive](https://frontendmasters.com/courses/webpack) | 深入介绍如何在项目中使用webpack2。视频是workshop上录制的，有现场讲师和学生的提问互动，非常赞。

## GraphQL && Relay
### 教程
名称 | 简介
---- | ----
[https://learngraphql.com](https://learngraphql.com) | 非常详细的介绍了graphql的基础用法，很好的入门教程。

## 其他
名称 | 简介
---- | ----
[http://flexbox.io/](http://flexbox.io/) | flexbox视频教程，共20个小视频，前13小节讲述了flexbox的各种属性，后7小节实例演示。
[Functional Programming in JavaScript](https://www.manning.com/books/functional-programming-in-javascript) | React生态圈中到处透露着函数式编程的思想，这本书对于函数式编程接触较少的人来说内容非常丰富，并且一些地方讲的比较深入，适合多次阅读。
[learnrx](http://reactivex.io/learnrx/) | 前面章节讲了大量的函数式思想(其实就是map,filter,reduce,concatAll,concatMap这五个函数啦)，后面引入Rx，并和数组进行对比，讲解Observable和array有什么联系和区别。


## 问答
问题  |  简介
---- | ----
[How to dispatch a Redux action with a timeout?](http://stackoverflow.com/questions/35411423/how-to-dispatch-a-redux-action-with-a-timeout/35415559#35415559) | 回答者是Redux的作者，阐述了如何在Redux中进行异步操作，什么情况下需要对异步操作进行封装，以及redux-thunk中间件的使用。
[Why is 'key' needed?](https://www.reddit.com/r/reactjs/comments/4mjdcf/why_cant_i_put_key_in_default_props_or_define_the/d3xwa6m) | 解释了为什么在一个React Elements数组中需要指定每个元素的key属性。
[what-does-webpack-mean-by-xx-hidden-modules](https://stackoverflow.com/questions/28858176/what-does-webpack-mean-by-xx-hidden-modules) | webpack运行时,控制台出现+n hidden modules的原因。

## Advanced
* [React PureComponent 源码解析](https://segmentfault.com/a/1190000006741060)
* [深度剖析：如何实现一个 Virtual DOM 算法](https://github.com/livoras/blog/issues/13)
* [React: Implementation Notes](https://facebook.github.io/react/contributing/implementation-notes.html)
* [reactjs源码分析-上篇（首次渲染实现原理）](http://purplebamboo.github.io/2015/09/15/reactjs_source_analyze_part_one/)

## Newsletter
* [http://reactjsnewsletter.com/](http://reactjsnewsletter.com/)
* [http://newsletter.fullstackreact.com/](http://newsletter.fullstackreact.com/)
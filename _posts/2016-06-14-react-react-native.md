---
layout: post
title: "React, React Native基本概念和名次解释"
description: "React/React Native基本名次解释"
category: "React/React Native"
tags: [React, React Native]
---
{% include JB/setup %}

# 基础名词解释

React,reactjs, React Native,Flux, Flex, reducer, action, store, state,redux,npm, node,elm,relay, graphQL, virtual DOM, ES6, ES5, JSX,webpack,browserify, babel, state/props,Immutability, strict,rnpm,codepush,flow,eslint

flow, 一个 JavaScript 的静态类型检查器

# 技巧
1. 用nuclide调试React Native : https://nuclide.io/docs/platforms/react-native/#debugging

# 问题收集
1. 升级react native(0.26.3 => 0.29.0) 以后不能正常工作，抛错: "Unable to resolve module react from...", ""

  	解决方法: node 滚回到4.0.0, npm 用2.14.2

2. Pod install 的时候抛: Invalid `React.podspec` file: no implicit conversion of nil into String.

   解决方法，升级ruy 到2.3.0
3. 在按钮事件里面获取网络数据，然后setState，界面没有刷新.

    最后发现是setState里面传的值没有变化导致的，愚蠢的错误。
4. 

# 参考
[谈谈React的核心入门知识](http://wwsun.github.io/posts/react-getting-started.html)

[Think in Reat](https://facebook.github.io/react/docs/thinking-in-react.html)

[探索React生态圈](http://strikingly.github.io/blog/2015/08/26/navigating-react-ecosystem/)

[React Native干货集合](http://www.debugnode.com/91.html)

[React Native With Redux](http://richardcao.me/2016/01/12/React-Native-With-Redux/)

[ECMAScript 6 入门](http://es6.ruanyifeng.com/)

[React Native架构之Redux](http://www.jianshu.com/p/09956d82bca6), 对Redux基本概念解释得比较清楚.

[Redux document](http://redux.js.org/index.html)
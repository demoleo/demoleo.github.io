---
title: 动态局部回归过程（转）
author: 西门熊二
layout: post
permalink: /loess-in-gif/
categories:
  - 程序设计
tags:
---
局部回归Loess作为简单线性回归和最近邻KNN思想结合的产物，不仅直观，而且比较灵活。在数据探索过程中，对二元散点图做局部回归是基本步骤。

在R中用loess()和lowess()函数即可简单实现局部回归。

[Simply Statistics][1]用图像解释了loess的过程。

![loess in gif][2]

 [1]: http://simplystatistics.org/2014/02/13/loess-explained-in-a-gif/loess/
 [2]: http://simplystatistics.org/wp-content/uploads/2014/02/loess.gif

---
templateKey: blog-post
title: Supervised Learning(监督学习)
date: '2018-06-23T16:38:44+08:00'
description: 回归和分类是属于监督学习中的一种
tags:
  - ML
---
回归和分类是属于监督学习中的一种

In supervised learning, we are given a data set and already know what our correct output should look like, having the idea that there is a relationship between the input and the output.

使用已经有的数据来预测, 比如历史房价来预测未来房价. 找出输入值和输出值的区别

Supervised learning problems are categorized into "regression" and "classification" problems. In a regression problem, we are trying to predict results within a continuous output, meaning that we are trying to map input variables to some continuous function. In a classification problem, we are instead trying to predict results in a discrete output. In other words, we are trying to map input variables into discrete categories.

监督学习分为: 分类和回归两种问题. 在回归问题中，我们试图预测连续输出中的结果，这意味着我们试图将输入变量映射到某个连续函数。 在分类问题中，我们试图预测离散输出中的结果。 换句话说，我们试图将输入变量映射到离散类别。

Example 1:

Given data about the size of houses on the real estate market, try to predict their price. Price as a function of size is a continuous output, so this is a regression problem.

从市场中给出真实的房价,尝试预测价格. 价格是一个函数的输出. 所以他是一个回归问题

We could turn this example into a classification problem by instead making our output about whether the house "sells for more or less than the asking price." Here we are classifying the houses based on price into two discrete categories.

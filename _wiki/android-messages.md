---
layout: wiki
title: message mechanism
cate1: Android
cate2:
description: message mechanism
keywords: Android
---

## 在工作线程里如何也能处理消息

方法一：

给线程关联一个 Looper.prepare()，然后调用 Looper.loop()。

方法二：

使用 HandlerThread。

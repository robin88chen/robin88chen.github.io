---
title: "《架構中的邊界概念》之一"
categories:
  - 架構決策
tags:
  - Architecture
---
### 前言
最近讀了幾本書，有**領域驅動設計**的、**架構模式**的、**重構**的，從這些書中漸漸有個關於**邊界**的想法概念在成形，試著把它整理出來，看看能不能形成一套思路。

### 邊界
第一次接收到**邊界**的概念，是在領域驅動設計的經典名著上。
![領域驅動設計--軟體核心複雜度的解決方法](/assets/images/ddd_book.jpg)
Eric Evans 帶給了我們 Bounded Context 的概念，

先把 Github Page 設定起來了。

Github 上的說明，照著步驟做只能給一個很陽春的站，其他的都要自己設計。要掛這個 [jekyll][jekyll] 幾乎是不能。更別說還要套個主題。除非自己在本機架好該用的 Ruby 什麼的。

所以，要換個方法，從 Github 上的 template 建立這個站。
[這裡有個][mm_starter]然後用來直接[建立][mm_generate]。

接下來，就是修改`_config.yml`檔案。

[jekyll]:https://jekyllrb.com/
[mm_starter]:https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/
[mm_generate]:https://github.com/mmistakes/mm-github-pages-starter/generate
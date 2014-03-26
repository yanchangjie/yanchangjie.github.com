---
layout: post
title: CSS Selector笔记
---

{{ page.title }}
================

<p class="meta">26 March 2014 - HangZhou</p>

这篇是补昨天的。昨天在逛[Hacker News](https://news.ycombinator.com/)的时候，看到一个好玩的东西————[CSS Diner](http://flukeout.github.io/)。正如网页中说明的
>It's a little game to help you learn CSS seletors

在这里我简单记录一下几个小题的解：

1. 第十题(Select all the things!)：*
2. 第十二题(Select every apple that's next to a plate): plate+apple
3. 第十三题(Select every pickle to the right of the bento): bento~pickle
4. 第十四题(Select the apple directly on a plate): plate>apple
5. 第二十六题(Select all even plates): plate:nth-child(even) or plate:nth-of-type(even)

小结：该网页相对来说是一个比较有趣的CSS选择器的小测试，总体难度偏简单，设计上网页右侧的提示比较人性化。题目的质量还有较大的提高空间，例如可以增加区别nth-of-type和nth-child的相关题型。nth-of-type和nth-child的区别可以在[这篇博客](http://www.zhangxinxu.com/wordpress/?p=1709)里找到，个人感觉讲得还算清楚。

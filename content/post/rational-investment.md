---
title: "如何在理财中胜出"
date: 2019-10-26T22:40:07+08:00
draft: false
tags: ["基金",]
categories: ["理财"]
author: "pinple"
---

## 大多数人是如何亏钱的？

最近看了几本关于理财的书——《小狗钱钱》《周期》《财务自由之路》、《富爸爸穷爸爸》，结合这一年短暂的理财经验，总结出一些自己的思考。

相信很多人一开始买股票都是追涨杀跌，看着股票涨就想买，跌了就想赶紧出掉及时止损，如果你一直这么操作，我保证你会把本钱赔光，为什么？可以看一下回形针的这期视频[【回形针PaperClip】为什么你炒股总是亏钱？](https://www.youtube.com/watch?v=_f0VoxypcCo&ab_channel=%E5%9B%9E%E5%BD%A2%E9%92%88PaperClip)。大多数不具备专业知识背景的人都是通过看新闻买股票的，而等到放出新闻来的时候往往已经晚了，消息比我们灵通的资本早就进场等着割韭菜了。《周期》这本书指出，股票的收益在你买入那一刻就决定了，而非卖出的时候决定的。

所以，买入的时机非常重要。《周期》这本书的核心思想就是：经济周期就想是钟摆一样，在两个极端来回摆动，当摆动到一个极端的时候，反弹的势能就越大。但是，个股的涨跌周期很难把握，所以我现在已经不买股票了。开始转战基金定投，基金相对股票而言更稳，如果找个大盘低点进场，并且长期持有，赚钱的几率是很大的。虽然现在大盘是2950点，但是我相信机会还是有的，要有耐心，等待大盘低于预期的时候再进入。

人是情绪化的动物，个人情绪很容器受到周围环境的影响，比如我在6月买基金的时候，每天都会去评论区看看大家怎么看，很多时候，基金涨一个百分点大家就会齐呼「牛逼！」，跌一个百分点的时候就开始骂骂咧咧。这种带有煽动性的言论很容易影响自己的情绪，因为当大家都这么说的时候，你很容易跟着相信。如果你跟大家操作一样，那么注定会得到跟大家的一样的结果，据统计，在A股至少有70%的账户都是亏钱的，要想赚钱，就得跟大家思路不一样。

## 如何保持理性？

怎么做呢？我得找到一个方法努力让自己远离其他股民的言论，但是我又想看基金的涨跌行情。我写了一个小工具[vlight](https://github.com/Neulana/vlight)，可以在收盘前（比如：下午14: 30）抓取基金的涨跌数据，如果超过了你设定的幅度，就会发一封邮件到你的邮箱，我使用的是QQ邮箱，然后在微信中绑定QQ邮箱，登录电脑版微信，这样在繁忙的工作中就会及时收到基金的行情，然后自己再根据行情进行补仓/建仓，值得指出的是，当幅度没有达到你的预期值时则不会触发发邮件。做这个工具的目的就是：***不过度关注每一天的涨跌情况进而影响情绪，但是又不能错过每一次加仓或者减仓的机会***。即，涨得太多减仓，跌得太多加仓。

仓库地址：[pinple/vlight](https://github.com/pinple/vlight)

如果读这篇文章的你也想使用，可以fork这个仓库，然后在[Travis CI](https://travis-ci.org)配置一下，设置环境变量：你的邮箱地址和邮箱密码，设置构建周期为daily。

![travis-setting.png](https://i.loli.net/2019/10/27/4YqUnGBXoZDi13u.png)

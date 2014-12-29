---
layout: post
title: "GZRuby第22次活动总结"
date: 2014-12-28 11:09
comments: true
categories:
---
各位Rubyist好！

这周六我们在广州T.I.T创意园的CCIC联合文创举行了[第22次的GZRuby
Party](https://ruby-china.org/topics/23285)，尽管天气较冷，还下起了小雨，但还是不能阻挡与会者的热情 :)

### 活动回顾

#### 分享内容

以下简单总结本次活动中各位讲师带来的精彩内容，点击主题名称后的链接可以直接在讲稿网查看演讲内容。

**1. 高金华 - 《 Sass 和 Compass 在 Web 开发中的实践》** [链接](http://jianggaowang.com/slides/48)

Sass 是一种拓展了 CSS3 规则的样式语言，提供了变量、函数、嵌套等便于 CSS 开发的特性，并可以编译成 CSS 代码应用于生产环境中。在这个主题中，高金华详细介绍了 Sass 的基本语法及使用，并结合生动的例子演示如何利用 Sass 的新特性来对样式代码进行良好的组织。

![](https://ruby-china-files.b0.upaiyun.com/photo/2014/b38be11c3eb16bce87d8b2d8d6c85ca1.jpg)

**2. 王振威 - 《 你不知道的 Nginx 》** [链接](http://jianggaowang.com/slides/49)

Nginx 是我们在生产环境中常用的HTTP和反向代理服务器，相信众多开发者（特别是后端）或多或少都会接触到。
但 Nginx 除了基本的反向代理、静态资源处理等功能外，还有不为人熟知的诸多应用场景。
来自 Coding.net 的王振威在演讲中介绍了 Nginx 的一些“冷门”功能，如正向代理，内部重定向，限制并发，配合 memcached 进行使用，配合 lua 进行使用等，可谓干货多多。

![](https://ruby-china-files.b0.upaiyun.com/photo/2014/089f892a0027775efc6090bf38090489.jpg)
![](https://ruby-china-files.b0.upaiyun.com/photo/2014/2dec11e62817c168384511047bf2bad6.jpg)

**3. 周建平 - 《 Token Based & Loose Coupling Auth in API designing 》** [链接](http://jianggaowang.com/slides/50)

在API设计中，需要仔细考虑如何进行用户验证和用户权限管理；同时，如何在前后端组织同一份用户权限的信息（knowledge）也是开发者需要斟酌的问题。
来自艾道信息咨询的周建平为我们讲解了基于 JWT(Json Web Token) 的 API 验证方法：在用户登录时利用用户非敏感信息和 secret key 组装的方式生成 JWT 并返回，客户端利用收到的 Token 来进行后续的验证；同时利用验证时返回的指令集来规定客户端用户的权限，以达到前后端代码松耦合的效果。

![](https://ruby-china-files.b0.upaiyun.com/photo/2014/e5346053aea7cd506f6a0de943efef74.jpg)
![](https://ruby-china-files.b0.upaiyun.com/photo/2014/5beb46306462f6ae1605f756d1eb3f92.jpg)
![](https://ruby-china-files.b0.upaiyun.com/photo/2014/8da028839b8c6e36d726cb828f91bc9f.jpg)

#### 即兴演讲环节

除了固定的讲师分享外，我们还加入了即兴演讲的环节，在场的小伙伴们就函数式语言聊起来了 ;)

![](https://ruby-china-files.b0.upaiyun.com/photo/2014/491fa5c38da94be000251986b4e37d16.jpg)

最后再放上合照一张！

![](https://ruby-china-files.b0.upaiyun.com/photo/2014/6deb35471f7e14d7471c2e912561f65b.jpg)
![](https://ruby-china-files.b0.upaiyun.com/photo/2014/c5fb2622cc8e5486f1ddaf71db9c6a56.jpg)
![](https://ruby-china-files.b0.upaiyun.com/photo/2014/e8e595ea420fe04b4cf876178fa228ce.jpg)

### 总结&展望

~~每到这个时候就会有很多人说“新的一年，新的希望”（我们也不例外,LOL）~~

随着本次 GZRuby 的顺利完成，2014年的活动也告一段落了，从1月份的[Rails Girls
](https://ruby-china.org/topics/16052)，3月份的[第17次活动](https://ruby-china.org/topics/17989)，再到本月的[第22次活动](https://ruby-china.org/topics/23285)，GZRuby 一直坚持下来，作为 Ruby 气氛并不是太浓厚的广州城的坚守。这里要感谢为活动提供场地的Strand Beer，FocusCom，铂涛酒店，CCIC联合文创，以及历次参加活动的讲师们和朋友们！

2015年 GZRuby 的活动会继续进行，活动频度仍旧为1个月1次，新的活动会在[官网](http://gzruby.org)，Ruby China 以及 GZRuby 的微信群中发布消息，同时我们也争取尽快建立 GZRuby 的微信公众号。

希望社区的朋友们继续多多支持，更欢迎为活动贡献主题，有任何意见或者建议欢迎直接联系我们。联系方式：
martin at beansmile.com, allen at dxhackers.com

### GZRuby 微信交流群

最后加上 GZRuby 微信交流群的二维码，欢迎感兴趣的朋友们加入！

![](https://ruby-china-files.b0.upaiyun.com/photo/2014/75f79a02aa41ea66f8274dbefed00928.png)

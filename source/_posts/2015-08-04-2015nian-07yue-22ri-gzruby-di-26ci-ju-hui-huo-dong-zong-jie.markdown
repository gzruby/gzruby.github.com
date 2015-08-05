---
layout: post
title: "[2015年07月22日]GZRUBY 第26次聚会活动总结"
date: 2015-08-04 22:45
comments: true
categories:
---
广州的Rubyist们，7月份的总结来了!


7月22日我们在广州市海珠区的 T.I.T 创意园里的 CCIC 联合文创前厅举办了 GZRUBY 的第 26 次聚会，以下是本次活动的总结：

### 1. 邓怀涛 - 《Ruby与微信开发那些事》
首先是由[邓怀涛](https://github.com/lanrion)带来的微信开发那些事儿，邓怀涛是一系列流行的微信开发gem的作者，例如 [weixin_rails_middleware](https://github.com/lanrion/weixin_rails_middleware) 和 [weixin_authorize](https://github.com/lanrion/weixin_authorize)等等。这些gem在国内有不少的使用者，包括一些已经初具规模的公司，有着广泛的影响。

邓怀涛的演讲中主要介绍了微信相关的系列gem，以及做这一系列开源gem的初衷。同时他也分享了在做开源项目的一些感受，例如一个人维护代码库的辛苦，命名gem时（weixin_authorize）的纠结，由于时间和精力的限制导致的测试不够完备和文档不完备的问题。当然也少不了针对微信开发平台的吐槽，例如客服不专业，回答问题永远回答不到点上。文档往往成为"文挡"，不是敲门砖，而是拦路虎等等。我们也期待大家能够一起动手来维护和完善这些开源项目，众人拾柴火焰高，一起把微信开发的生态圈活跃起来。

![](https://ruby-china-files.b0.upaiyun.com/photo/2015/5696ec7c58ec7bf6bd5543374fae3c3f.jpg)


### 2. Rain Chen - 《友约v0.4的开发经验总结 for gzruby》

接下来的主题是两个当红技术的结合，当微信开发平台遇到炙手可热的React之后，会擦出怎样的火花？[Rain Chen](https://github.com/rainchen)是[Beansmile](http://beansmile.com/)团队CTO，专注Web开发已有十余年经验。最近Beansmile在自己的内部项目[友约](http://youyue.so/)中尝试了使用React进行微信开发，这次分享就是开发过程中的经验总结。



Rain 首先介绍了友约项目的由来，为什么要打造一款基于微信平台的朋友聚会签到工具。接下来的技术部分，主要讲到了微信平台的一些限制，例如只有备案之后才能在分享到朋友圈的页面执行js代码，非常见的 *.so 域名不能通过校验，如果说天朝已经是Hell模式，某种意义上微信平台是Hell+模式。此外看起来很美的模板消息在使用起来时也是诸多限制。除了和上面邓怀涛提到的一样的文档不清晰问题之外，Rain还着重探讨了如何调试微信平台应用。


和React结合部分，Rain重点提到了自定义的Img这个component以及为此开发的一个gem [react-rails-img](https://github.com/beansmile/react-rails-img)，欢迎Ruby党使用。此外Rain还探讨了form field默认值问题(数据双向绑定)以及component之间的通讯问题，详细内容可以从文末的讲稿下载链接中获取。


ps，图中有彩蛋

![](https://ruby-china-files.b0.upaiyun.com/photo/2015/93e2c85b45e3b2dcfad1abb97d00198f.jpg)



### 3. 杜小龙 [aka Kevin Du] - 《关于微信开发的一些思考》


Kevin是[Beansmile](http://beansmile.com/)团队的产品经理，目前负责团队内部的"班级助手"项目开发。班级助手是一款基于微信的通知工具，Kevin在打磨这款产品的时候，也对微信开放平台上适合做什么产品，适合什么样的场景做了深入的思考。


Kevin的分享主要讲述了订阅号、服务号、企业号的不同，这些不同和限制分别会引导用户怎样使用基于微信平台开发出来的应用。对于订阅号，更多的是运营的需要，以内容来支撑。对于服务号，更多的是以推送功能为主，以推送消息触发用户使用。而企业号则是企业内部沟通的平台，但是企业号面临的挑战是工作生活分不开，这样会对部分用户产生干扰，毕竟微信的口号是一种"生活"方式，工作的内容掺杂进来是否合适，这是个值得探讨的话题。


延伸阅读：《[微信会取代哪些app？](http://www.jianshu.com/p/cdfc11ab579d?utm_campaign=hugo&utm_medium=reader_share&utm_content=note&utm_source=weixin-timeline&from=timeline&isappinstalled=1)》


![](https://ruby-china-files.b0.upaiyun.com/photo/2015/9206cb34dfc52a64049a8d2b72b31e03.jpg)

### 4. 校寻团队 - 《校寻互联网推广》


这是GZRuby为数不多的非技术性话题，以前GZRuby关注纯技术内容比较多，这次由校寻团队带来的推广案例也让大家得以管窥项目落地推广的流程，并能够对推广（尤其是校园推广）的成本有个大致的了解。


校寻团队的介绍从"小猪导航"这样的具体案例入手，说明即便是技术没有压倒性的优势，凭借着敏锐的市场嗅觉和良好的推广效果，还是能在市场上占据一席之地。接下来的推广方式介绍中，特别对比了扫楼、摆摊、社团、网络以及微信公众号等方式的投入产出比，相信对大家以后的产品推广有一定的借鉴意义。


![](https://ruby-china-files.b0.upaiyun.com/photo/2015/a9060293854a75c35066c399a3eb9cfc.jpg)


放一些现场照片

![](https://ruby-china-files.b0.upaiyun.com/photo/2015/d9a429949bea327a0e6410b2daed3f2c.jpg)



![](https://ruby-china-files.b0.upaiyun.com/photo/2015/0eed1b45cc51454049905e208d8ce57a.jpg)



### 小结和预告


本次活动的讲稿可以从[这里](http://pan.baidu.com/s/1bnfQvpX)下载，下次GZRuby的活动和本月的[RailsGirls](http://railsgirls.com/guangzhou)活动合办，希望大家踊跃报名，帮助女性朋友进入到程序开发的美妙世界！

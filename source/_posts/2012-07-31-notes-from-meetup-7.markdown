---
layout: post
title: "Notes from meetup 7"
date: 2012-07-31 13:55
comments: true
categories: 
---



<img src="/images/meetup7.jpg" style="width: 800px" alt="It really is a ruby party" title="Join us every other month!" />

Last wednesday we had a great turnout for the 7th gzruby meetup! It was a blast with tons of great people, some nice talks, and a lot of fun. I'd say this last event was maybe more of a ruby party than a developer meeting, and that's not a bad thing!

It's been a year since our first event, and already we've seen several projects started by members of our group referring clients to one another, or working together on a big project. We started this event to enable this kind of cooperation, and we couldn't be happier that we have been successful. Remember, the more ruby projects get done here in South China, the more people will be interested to start new projects, and we all do better!

Its great to continuously meet new members, and to reconnect with the old ones. Lets spread the word and make **gzruby** a great place for all of us to find friends, learn from each other, and do great business together!

[Strand Beer](http://weibo.com/strandbeer) once again supplied us with plenty of homebrew goodness. Keep making that great beer fine ruby fellow!

* **Integrating Rails with Wordpress <http://thenanfang.com>**
   
  Leon presented his company's latest project (a [gzruby](http://gzruby.com) connection): [TheNanfang.com](http://thenanfang.com). He described how he and his team were able to use Rails to win the project, by building a very rapid working prototype. After winning the project, they were able to execute and complete the project on time using standard Rails best practices and good old hard work. Leon and Rain also described how they were able to marry the de-facto blogging platform WordPress into their Rails site. We are all proud of their work and its an excellent addition to the group of ruby projects based here in South China. Great job [beansmile](http://beansmile.com)!
   
  Presented by [Leon Du](http://beansmile.com) 
  
* **Introducing FriendsMap.net <http://friendsmap.net>**
   
   [@cantin_](http://www.weibo.com/n/cantin_) just released [FriendsMap.net](http://friendsmap.net), a toy project that displays your social network friends on a map. He gave a short talk about what he used to put it together, and gave a quick demo. 
   
   It is a project to pratice using the OAuth2 APIs and google maps. You can now use the site to find your Facebook, Twitter, QQ, and your Sina Weibo friends. There is a China version that works with Weibo and Baidu maps, or you if available to you, you can use Google Maps to location friends around the world.
  
  Presented by [Cantin Xu](https://github.com/cantin) 
  

* **Explaining Session hijacking and why we need CSRF protection <http://guides.rubyonrails.org/security.html>**

  [@jevgz](https://github.com/jevgz) showed us how easy it is for an attacker to create a site that could change the user's password just by mousing over a link. He showed us step by step what can happen if you don't follow Rails best practices and leave your site open to attack. Its a stark reminder of how to important it is to stay on top of current security trends. It was also a great explanation on why we need the CSRF tags in our Rails projects. If you haven't read the [Rails security guide](http://guides.rubyonrails.org/security.html), I suggest you do so soon.
   
  Presented by [@jevgz](https://github.com/jevgz) 
  


* **Textilize <http://github.com/kudelabs/textilize/>**
 
  [@ifosen](http://www.weibo.com/ifosen) recently released a new gem that provides the Rails 2.x textilize helper methods in Rails 3.x. In case you are updating an older app that relied on these functions, you can simply drop this gem into your Gemfile and you're ready to go. There are other gems that already do this, but these gems utilize the latest version of Redcloth, which is (in our opinion) unneccessarily large and complicated, requiring native extensions to be compiled. Textilize avoids this extra dependency by including the original RedCloth.rb written by _why.
  
  @adevadeh stressed the importance of anlysing your gemfile to reduce external dependencies. Make sure that everything you rely on in something you really need. Also, don't be afraid to publish a gem, even if its a small one. You never know who else might find it useful, and you may get something back you never expected!
   
  Presented by [Mysen](https://github.com/mysen) and [@adevadeh](https://github.com/adevadeh) 

  
--- 


Thanks very much to our presenters for sharing. We really appreciate that you stood up to share what you've been working on or show us something that may help us in our daily work. We hold these meetings to learn from each other, so be sure to give yourself some time to show other developers what you have learned.

### See you at the next meeting, scheduled for **Wed,  September 19, 2012**

### Follow [@gzruby](http://www.weibo.com/gzruby) on Sina Weibo! 


<img src="/images/meetup7-2.jpg" style="width: 800px" alt="It really is a ruby party" title="Join us every other month!" />


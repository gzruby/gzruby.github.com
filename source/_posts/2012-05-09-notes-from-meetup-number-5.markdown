---
layout: post
title: "Notes from meetup #5"
date: 2012-05-09 15:20
comments: true
categories: 
---

OK, this is a bit late. The last gzruby meeting we held, on March 21, was a great success: we had visitors from Shenzhen and a [Rails hero from the US](http://twitter.com/#!/danielkehoe); we imbibed some [great beer made by one of our members](http://www.weibo.com/strandbeer); and to top it all off we had some really fun and exciting presentations.

* **Working with Bootstrap <http://twitter.github.com/bootstrap/>**
  
  With Rails, we have a very stable and mature back-end framework that allows us to write code in a standard way. Bootstrap from Twitter provides a similar functionality for the front-end. Rather than rolling your own css again and again, bootstrap gives you a standard way to layout your HTML pages, a standard way to style buttons and other elements, and it is generally much better than anything you could come up with on your own. 
   
  Presented by [Leon Du](https://github.com/leondu)

* **Introducing Web-App-Themes <https://github.com/pilu/web-app-theme>**

 We've all done it 20 times. When starting a new app, we have to choose how to style it. We want it to look nice, but don't want to spend time designing colors or write out the same HTML. Web App Themes takes care of this for us. But rather than an engine or an almost ready made app, it simply helps you generate HTML and CSS for you to use as you see fit. For certain projects where you just need to get started with some reasonable good looking HTML and CSS, Web App Themes may be your best option.
  
  Presented by [@shaokun](https://github.com/shaokun)

* **The Wonders of Pry <https://github.com/pry/pry>**
  
  Pry is an IRB replacement that will knock your socks off. William certianly knocked our socks off with his presentation! Imagine being able to treat your entire ruby process' object space like a simple filesystem, where you can travel down paths to inspect data, `cd ..` to go back, and search down another branch. You can even ask questions like "Which method on (this object) could give me (this result)?" If you are a ruby developer and haven't seen pry, you need to give it a look.
  
  To invoke pry in your rails app, just add the line: `(require pry; binding.pry) #!!`
  
  Presented by William
  
* **Rails App Templates <http://railsapps.github.com/>**
  
  The Rails ecosystem is full of choices, you've got gems and engines, fixture generators and testing frameworks. This can get overwhelming as technologies change fast. That's where this project comes in. It attempts to provide up-to-date documentation on the latest best-practices with Rails. Whether its building apps that use Devise for authentication, or how to integrate bootstrap into Rails, Rails Apps has you covered. Check out their extensive list of template apps and detailed tutorials.
  
  Presented by [Daniel Kehoe](http://www.linkedin.com/in/danielkehoe)
  
--- 


Thanks very much to our presenters for sharing. We really appreciate that you stood up to share what you've been working on or show us something that may help us in our daily work. We hold these meetings to learn from each other, so be sure to give yourself some time to show other developers what you have learned.

### See you at the next meeting, scheduled for Wed, May 16, 2012

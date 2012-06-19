---
layout: post
title: "Notes from Meetup 6"
date: 2012-05-29 15:30
comments: true
categories: 
---


<img src="images/meetup6.png" style="width: 800px" alt="We <3 Ruby!" title="Join us every other month!" />

I think we can all agree that the meeting held May 16, 2012 was one of our best yet. We had a bunch of new visitors. Its thrilling to see young rubyists joining our ranks, and at this meeting we had 5 recent graduates who all learned ruby on their own. We also love to see visitors from other platforms, we welcome anyone who has a passion for technology and software development.

At this meeting we had the honor of hosting guests from China Telecom. They were looking to find the next great mobile app and learn about what current mobile app developers are thinking about. Visitors of all types are welcome - from different disciplines and different platforms. Developers don't work in a vaccum, we need to work together with others to make sure our products get out into the world. 

Thanks again to [Strand Beer](http://weibo.com/strandbeer) for the wonderful refreshment!

* **Namespace-less Rails Engines <http://github.com/shaokun/nl-engine/>**
  
  As we develop more and more applications, we find ways to make our life easier and start to re-use parts of an app in the next project. Hopefully, as time goes on, we can build reusable components that we can use in future apps to speed up development. In static, client side developemnt, this kind of code reuse is common and easily accomplished. In web development, when dealing with server side code, HTML, javascript and databases, it can get complicated. As of Rails 3.x Engines are very handy and a great way to share code between apps. But you don't want exactly the same code in every project. Sometimes one client wants to be able to delete widgets, another client wants to edit widgets, and a third client wants to be able to copy her widgets. So the next question is, how do we share common code between apps, and use ruby's object oriented nature to extend functionality.
  
  In his talk, Shaokun described a technique to make sharing code easier by building Rails Engines that can be overridden cleanly. The engine code is kept seperate and any custom functionality is implemented at the project level. Your engine can live in a git submodule, and all of your custom code - model, controller, and views - lives in your current project. This separation makes it easy to continue to maintain the core functionality while being able to satisfy each client's needs.  
   
  Presented by [伍少坤](https://github.com/shaokun) 

* **Angular.js <http://angularjs.org/> ([slides](http://igorminar.github.com/ng-slides/angular-intro/index.html))**
 
  Rails is a great framework for the server side. It gives you a well-defined structure and lots of tools for managing data and code on the server. Yet modern web apps have matured to the point where much of the interesting parts of the app are on the client side. On this side Rails shows some weakness - you need to mix several languages, js, css, html, erb into templates that are compiled server-side and then sent to the browser fully-baked. In today's world of highly interactive and dynamic web applications, the Rails way is simply no longer good enough.
  
  [Angular.js](https://github.com/angular/angular.js) is one of many projects attempting to fill in this gap. It is a way to manage client side view logic compltely in the browser using pure HTML and JS. Similar to projects like [ember.js](http://emberjs.com/) and [backbone.js](http://backbonejs.org/), it allows you to define html templates and fill them with live data, either taken from a server or computed in the browser with user input. 
  
  Angular caught our attention because it integrates well with existing technologies, it doesn't require you to move everything over at once. You can implement just part of a page in angular, if you wish, and change the rest slowly over time. It also has a very clean way of dealing with data from the server and integrating it into the page. 
  
  Paired with a strong server-side framework like [Rails, Angular](https://github.com/IgorMinar/angularjs_rails_demo) could be the the missing piece. The piece that takes us into a new world of truly interactive, user friendly, web apps. 
   
  Presented by [@adevadeh](https://github.com/adevadeh) 

  
--- 


Thanks very much to our presenters for sharing. We really appreciate that you stood up to share what you've been working on or show us something that may help us in our daily work. We hold these meetings to learn from each other, so be sure to give yourself some time to show other developers what you have learned.

### See you at the next meeting, scheduled for Wed,  July 18, 2012

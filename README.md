# <img src="https://cdn.auth0.com/blog/aurelia-logo.png" width="45">   Aurelia Starter Guide
_This guide is not affiliated with Durandal, Inc. (the baller people behind Aurelia)_.

### Purpose
This guide is intended to familiarize you with Aurelia and the Aurelia ecosystem. This is _not_ intended to be a complete guide for learning to build applications with Aurelia (I'll let people much more experienced than me do that). My hope for this guide is not to give you a solid foundation for building Aurelia applications, but to give you a solid foundations for _learning_ how to build Aurelia applications.

### Introduction
>[Aurelia](http://aurelia.io) is a next gen JavaScript client framework for mobile, desktop and web that leverages simple conventions to empower your creativity.

Aurelia is a forward-thinking Javascript framework for building web applications. By _forward-thinking_, I (and they, I stole the description from their homepage) mean that Aurelia itself and apps built using Aurelia leverage the latest and greatest web technologies. This includes but is far from limited to Ecmascript 6, Web Components, Ecmascript 7, and they even have strong support for using languages that compile to Javascript like TypeScript and CoffeeScript. The project was started and is headed by the creator of the [Durandal](http://durandaljs.com/) framework, [Rob Eisenberg](https://twitter.com/eisenbergeffect). Rob started the framework after disagreeing with the direction that the Angular team (of which he used to be apart of) was taking Angular 2.

### Before Diving Into Aurelia
As stated in the introduction, you will be using the next-generation of web technologies to build your Aurelia applications. Because of this, it's probably a good idea to at least familiarize yourself with some of these technologies before learning a framework that uses them. Here I'll list some of the most important ones, and some resources for learning about them.

#### ES6/7
##### Classes
+ [An introduction to ES6 classes](http://javascriptplayground.com/blog/2014/07/introduction-to-es6-classes-tutorial/)
+ [A Guide to ES6 classes](http://ilikekillnerds.com/2015/02/a-guide-to-es6-classes/)
+ [Exploring ES6 by Axel Rauschmayer - Chapter on classes](http://www.2ality.com/2015/02/es6-classes-final.html)
  + This one can get pretty technical at points, but this guy has written some of the best ES6 content that I've read. Worth the read if really want a good understanding of ES6 classes.

##### Modules
+ [Getting Started with ES6 Modules - EvilTrout](http://eviltrout.com/2014/05/03/getting-started-with-es6.html)
+ [Understanding ES6 Modules - Sandeep Panda](http://www.sitepoint.com/understanding-es6-modules/)
+ [Exploring ES6 by Axel Rauschmayer - Chapter on modules](http://www.2ality.com/2014/09/es6-modules-final.html)

##### Decorators
+ [Exploring ES2016 _(ES7)_ Decorators](https://medium.com/google-developers/exploring-es7-decorators-76ecb65fb841)

#### Web Components
+ [A Guide to Web Components - CSSTricks](https://css-tricks.com/modular-future-web-components/)

#### jspm/SystemJS
Modern package manager and module loader for using modules of any format.
+ [jspm.io](http://jspm.io/)
  + [jspm Getting Started documentation](https://github.com/jspm/jspm-cli/wiki/Getting-Started)
  + [Simplifying the ES6 workflow with jspm](http://www.joezimjs.com/javascript/simplifying-the-es6-workflow-with-jspm/)
+ [SystemJS](https://github.com/systemjs/systemjs)
  + [ES6 Modules with System.js](http://blog.mebooks.co.nz/es6-modules-with-system-js/)

#### Gulp
Build system.
+ [Learning Gulp - Getting Started with the Front End Factory](http://hmphry.com/gulp/)
+ [Level Up Tuts Videos on Gulp](http://leveluptuts.com/tutorials/learning-gulp)

### Getting Started
The best place to get started using Aurelia is [the official Aurelia Get Started guide](http://aurelia.io/get-started.html). Once you know a little about Aurelia after going through that guide, it might be helpful to then go through [this guide by Ryan Chenkie](https://auth0.com/blog/2015/08/05/creating-your-first-aurelia-app-from-authentication-to-calling-an-api/) that covers a bit more ground than the official tutorial. As with basically everything, the best way to learn is by doing, so after you're comfortable with the basics of Aurelia, try to make a small application on your own and refer to the resources in the next section for if and when you get stuck.

### Resources/Ecosystem
One of the best things about the Aurelia community is that it is incredibly active despite how young the framework is. You should have no problem getting a timely answer to any question you might have if you use these resources. 

+ [Aurelia on Github](https://github.com/aurelia)
  + The Aurelia framework itself is fairly lightweight, with most functionality coming from plugins that you can use or not use as you wish. You'll have noticed this if you went through the official Get Started guide and saw the massive `package.json` file.

+ [Aurelia Gitter](https://gitter.im/Aurelia/Discuss)
  + The Aurelia Gitter is by far the most active Gitter channel I've seen. Everyone from the creator to the core developers to beginners are there all day talking about the state of the framework and answering any questions. Every time I've gone on there's been at least one core developer there helping people out. Since Aurelia is such a young framework, it has no where near the external resources currently as other frameworks like Angular 1.x or Ember. Because of this, this Gitter channel will probably be the best place to seek answers to any questions you might have. 

+ [Aurelia Blog](http://blog.durandal.io/)
  + Blog posts from the Aurelia developers.

Pull requests are very much welcome.
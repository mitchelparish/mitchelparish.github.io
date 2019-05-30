---
layout: post
title:      "Rails + JavaScript"
date:       2019-05-30 21:52:53 +0000
permalink:  rails_javascript
---


I was excited to begin the JavaScript portion of the curriculum following the completion of my initial Rails project. I had become very comfortable with Ruby and my confidence allowed me to have a lot of fun with it, so it was a little hard leaving that world behind and starting fresh with a new language. One thing that’s apparent after spending so much time writing Ruby is that JS is ugly – you really can’t appreciate things until you step away and look back from the other side.  

A thousand curly braces and semicolons later I began my Rails + JavaScript portfolio project. The goal of the project is to add some minimal JS functionality to an already functioning app. While still a great time tinkering and problem-solving, this was definitely my least favorite of the Flatiron projects. Adding features “just because” goes against my minimalist mindset but I do see the value of the experience and the likelihood of a future client requesting similar projects.

**Getting Started**

To build off of your first Rails project you’ll need to add a few new gems, `jquery-rails` and `active-model-serializers`. Following `bundle install` you’ll want to create a JavaScript manifest file `application.js` and within that set your requirements:

```
//= require jquery3
//= require jquery_ujs
//= require activestorage
//= require_tree .
```

Then you can create separate JavaScript files for individual concerns. The `require_tree .` in the manifest file will ensure that your separate JS files load from the Rails Pipeline. 

**Features I Added**
Rails API - JSON translated into JS model objects
Dynamic form handling for campsite reviews
Campsite reviews rendered/expand via JS
User profile page rendered via JS

**One More To Go**

It’s been a very hard month. Aside from personal obligations I’ve been going back and forth working on this project and completing the React curriculum. There is one more week of instruction and then it’s off to my last project and graduation beyond that. The finish-line for this particular journey is in sight, however the potential for continued learning is infinite and that really excites and motivates me. 

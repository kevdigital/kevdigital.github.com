---
layout: post
title: "Style Changes and a New Project"
description: ""
category: 
tags: [coding]
loc: "cincinnati,oh"
---
{% include JB/setup %}

I revisited my blog here today and decided some style changes were in order. Since I am using the jekyll-bootstrap gem for this blog I figured I should use Twitter Bootrap's responsive features. 

I made the container and row div's fluid to now be more responsive when resizing the browser window and when viewing on mobile devices. 

Using some other CSS tips I have learned these past few months I was able to refactor my code and correct some mistakes I made the first time around. The text in this post for example is more readable.


<h2>Workout Log app and Ember.js</h2>

I've been playing around with starting a new project recently. I want to get some experience using a javascript framework to create a rich native-like web application. I've chosen Ember.js as the framework that I want to work with first. 

To learn with I will start by building a simple Workout Log app that allows users to sign in, create routines that they use frequently then quickly and easily log workouts. 

To power the persistence layer of the app Ruby on Rails provides a way to serve up json data to Ember.js as an API. The tutorials on Railscasts have been very helpful learning how to get started on this project. Will update later on my experience with Ember.js!
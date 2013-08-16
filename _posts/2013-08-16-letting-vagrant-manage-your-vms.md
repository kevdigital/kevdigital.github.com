---
layout: post
title: "Letting Vagrant Manage Your VMs"
description: ""
category: 
tags: [coding]
loc: "cincinnati,oh"
---

As mentioned in a previous post, I have been using Windows as primary dev environment, running a Ubuntu virtual machine to perform the actual dev work. This setup worked just fine for working on my own personal projects, but I kept reading on forums and Reddit about people recommending Vagrant enough that I decided to check it out.

Why I Use Vagrant
------------
One of the biggest reasons for me personally in making the switch to Vagrant is that it saves me time in setting up a new VM if I need to start working on a new machine. I currently have a Desktop PC at home, a laptop, and a couple different PC's I use at work from time to time. 

With Vagrant, I can provision my ubuntu server to include all the packages and servers I need and be ready to go in no time. I keep my vagrant virtual box files on Dropbox, along with other Sublime Text 2 and MovaXterm. I simply connect my new machine to my Dropbox, and I'm good to go. That, with hosting code on Dropbox and Github, I am never tied to a certain machine's local files.

Why Others Use Vagrant
--------------------
Now, this could very well be a reason I too use Vagrant in the future, but I can already see how it is helpful in a team of developers and in a professional environment. You can setup your Vagrant box to mirror the production servers that you are using, then share that with the rest of your team so that everyone is on the same environment when working on your application.
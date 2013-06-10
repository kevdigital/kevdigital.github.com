---
layout: post
title: "Best of Both Worlds: Coding with Ubuntu in a Virtual Machine on Windows 7"
description: ""
category: 
tags: [coding]
loc: "cincinnati,oh"
---
{% include JB/setup %}
Up until recently I felt most comfortable using Linux as my development environment. More specifically Ubuntu 12.04. For portability I had this installed as a second OS on my laptop and to avoid moving files around between machines I tried only using the laptop when doing any dev work. 

This became a bit of a pain since when at home being an avid PC gamer I primarily use a desktop PC running Windows 7. I was looking for a way to use my desktop for doing dev work at home without having to reboot whenever I wanted to switch between Ubuntu and Windows.

Eventually I came across a very informative post by Sam Saffron about [being more efficient](http://samsaffron.com/archive/2013/05/03/eliminating-my-trivial-inconveniences) with the tools you use. He describes his dev environment as using Windows and running Ubuntu in a Virtual Machine.

In learning about Web Development I have read plenty of opinions on which environment is the best and really it's all subjective, whatever you are most comfortable with is most likely best for you. But I had not heard of anyone using this particular setup of Windows with a VM running Ubuntu. Being a lifelong Windows user it only makes sense I am more comfortable there so adding in the power of a linux shell it seemed like a perfect fit.

Now, I hadn't had much experience using Virtual Machines prior to this so I had to do some research first to see what I was getting into. After looking around I found a very helpful [walkthrough](http://www.psteiner.com/2012/04/rails-3-on-windows-ubuntu-on-virtualbox.html) from Philip Steiner. It's just over a year old but I still found the information to be relevant. 

Using VirtualBox I was able to setup a Ubuntu VM and get my RVM and other packages installed. Once that is up and running I installed [MobaXterm](http://mobaxterm.mobatek.net/) thanks to Sam's post. MobaXterm allows me to SSH into the VM and have my linux terminal running outside the VM window. This makes it much easier as I can look up info from Stack Overflow in my Windows Chrome session and copy/paste right into the MobaXterm window. 

I'm really enjoying this new dev environment. I can stay in my Windows session with all my music and other fun stuff and fire up my dev work whenever I need to. Then when it's time for a break with a few clicks I'm jumping into a game of Dota2 :D




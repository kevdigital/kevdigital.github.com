---
layout: post
title: "Blog created with jekyll bootstrap"
description: ""
category:
tags: [coding]
loc: "cincinnati, oh"
---
{% include JB/setup %}

This blog was created using the <a href="jekyllbootstrap.com">jekyll-bootstrap</a> blogging framework. I love how jekyll enables me to create posts and maintain my blog "like a hacker". I open up my code in Sublime Text 2, run a rake command and I'm off and writing.

The flexibility is really nice and I've been experimenting with using the YAML Front Matter. By adding a custom field in the Front Matter of my posts, I can display a location for wherever I am making this post from.

	---
	loc: "cincinnati, oh"
	---

This enables me to use {{ page.loc }} within my post.html file and easily add it to the header of each post!
---
layout: page
title: kevinleugers.me web dev blog
tagline: 
---
{% include JB/setup %}

<h2>Blog Posts</h2>
<br>

<ul class="posts">
  {% for post in site.posts %}
    <b><li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li></b><br>
    {{ post.content | strip_html | truncatewords: 60 }}
    <p><a href="{{ post.url }}">Read more...</a></p>
    <hr>
  {% endfor %}
</ul>
<br>
 <h2>Useful Links</h2>
<br>
<ul class="posts">
  <li><span>30 Dec 2012</span> &raquo; <a href="http://huangzhimin.com/">Richard Huang's blog</a></li>
  <li><span>29 Dec 2012</span> &raquo; <a href="http://www.reddit.com/r/webdev">Reddit/r/webdev</a></li>
  <li><span>29 Dec 2012</span> &raquo; <a href="http://ruby.railstutorial.org">Ruby on Rails Tutorial</a></li>
  <li><span>29 Dec 2012</span> &raquo; <a href="http://guides.rubyonrails.org">Ruby on Rails Guides</a></li>
  <li><span>29 Dec 2012</span> &raquo; <a href="http://www.udacity.com">Udacity - free online university</a></li>
</ul>


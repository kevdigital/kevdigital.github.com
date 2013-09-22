---
layout: page
title: kevinleugers.me web dev blog
tagline: 
---
{% include JB/setup %}

<h2>Recent Bloggings</h2>
<br>

<ul class="posts">
  {% for post in site.posts %}
    <b><li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li></b><br>
    {{ post.content | strip_html | truncatewords: 50 }}
    <p><a href="{{ post.url }}">Read more...</a></p>
    <hr>
  {% endfor %}
</ul>
<br>
 <h2>Useful Links</h2>
<br>
<ul class="posts">
  <li><a href="http://railscasts.com">Rails Casts</a> &raquo; very helpful screencasts on many different Ruby on Rails related topics</li>
  <li><a href="http://www.reddit.com/r/webdev">Reddit/r/webdev</a> &raquo; Reddit's web dev community</li>
  <li><a href="http://ruby.railstutorial.org">Ruby on Rails Tutorial</a> &raquo; Michael Hartle's excellent guide for Ruby on Rails</li>
  <li><a href="http://guides.rubyonrails.org">Ruby on Rails Guides</a> &raquo; The official Ruby on Rails docs</li>
  <li><a href="http://www.udacity.com">Udacity - free online university</a> &raquo; I owe Udacity a lot in getting me started in web development. Their courses are fantastic. A great way to expand your knowledge</li>
</ul>


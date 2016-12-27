---
layout: page
title: Yitian's world!
---
{% include JB/setup %}


## Introduction

 
![alt text][logo]

[logo]: https://github.com/yitianxu/yitianxu.github.io/blob/master/image/self.png?raw=true
<br />

Author 

|--------|-----------|-----|
| Name   | Yitian Xu |
| Email  | yitian.xu@hotmail.com | 
| Github | yitianxu | 

<br />

> My name is Yitian Xu, born in China, currrently live in York, UK.  
> I am traveling nomand, already explored 7 continents around the world.  <br />
> Also I have passion to software advocate. 


----

## Posts


Here's the "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


---

### Thanks to Jekyll

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)


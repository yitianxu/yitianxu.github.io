---
layout: page
title: Yitian's World!
---
{% include JB/setup %}

### Me ?

![alt text][logo]

[logo]: https://github.com/yitianxu/yitianxu.github.io/blob/master/image/self.png?raw=true
<br />

|----------|-----------|-----|
| Name   | Yitian Xu (Aka. Michael sometimes)| 
| Email  | yitian.xu@hotmail.com | 
| Github | yitianxu | 
| Facebook  | [Yitian Xu](https://www.facebook.com/yitian.xu) |
| instagram | [@yitianxu](https://www.instagram.com/yitianxu/?hl=en) |

<br />

#### Bio
> **Bad** / **Unreliable** / **Easily distracte** <br />
> <br />
> Yitian Xu, made in China, running in York, UK (currently).  
> Traveling nomad: already explored 7 continents around the world.  <br />
> Love programming: Progress (8 years+), C (5 years+), Python (2 years+), Javascript, etc <br />
> Amateur Photpgrapher <br />
> Foodie. <br />


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


---
layout: single
author_profile: true
title: "What Are We Doing Here?"
date: 2023-04-05 09:00:00 +0000
show_date: false
read_time: false
last_modified_at: 2023-05-11 10:23:00
header:
  overlay_image: /assets/images/AlienLandscape02.jpeg
  overlay_text: "hello"
  show_overlay_excerpt: true
  #og_image:
  #overlay_color: green
  caption: "Keep Looking Up!"
  actions:
    - label: "Do Cool Things"
      url: /index.html
excerpt: "Astronomy: Shaken Not Stirred"
#tagline: "tagline"
classes: wide
---
**This Website** will be about amazing stuff

![A comet over an exoplanet](/assets/images/ExoplanetComet_woodcut.jpeg)

# Latest Episodes
<ul>
  {% for post in site.posts %}
  <li>
    {{ post.date| date:"%m-%d-%Y" }} // <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
  {% endfor %}
</ul> 

---
layout: post
sidebar: left
subheadline: Templates
title:  "Страница/публикация с левой боковой панелью"
teaser: "Это пример страницы/публикации с боковой панелью слева.."
breadcrumb: true
tags:
    - post format
categories:
    - design
image:
    thumb: gallery-example-3-thumb.jpg
    title: gallery-example-3.jpg
    caption_url: http://unsplash.com
---
*Feeling Responsive* shows metadata by default. The default behaviour can be changed via `config.yml`. To show metadata at the end of a page/post just add the following to front matter:
<!--more-->

~~~
show_meta: true
~~~

If you don't want to show metadata, it's simple again:

~~~
show_meta: false
~~~


## Other Post Formats
{: .t60 }
{% include list-posts tag='post format' %}

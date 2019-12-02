---
layout: blog
title: Blog
date:   2019-12-02
author: Cameron Taylor
permalink: /blog/
---

My Blog

{% include base_path %}

{% for post in site.blog %} {% include blog.html %} {% endfor %}

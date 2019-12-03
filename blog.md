---
layout: blog
title: Blog
date:   2019-12-02
author: Cameron Taylor
permalink: /blog/
---

[Blog](https://cameronntaylor.github.io/blog/) | [My Personal Website](https://cameronntaylor.github.io/)

<div class="posts">
  {% for post in site.posts %}
    <article class="post">
      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
      {{post.description}} Tags: 
      {{post.tag}}
      <!----- <div class="entry">
        {{ post.excerpt }}
      </div> ---->
      <!--{{ post.tag }} -->
    </article>
  {% endfor %}
</div>

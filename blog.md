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
      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.date | date: "%B %e, %Y" }}
      <br>
      By: {{post.author}}
      <br>
      {{post.description}} 
      <br>
      Tags: {{post.tag}}
      <!----- <div class="entry">
        {{ post.excerpt }}
      </div> ---->
      <!--{{ post.tag }} -->
      <br>
      <br>
      <br>
    </article>
  {% endfor %}
</div>

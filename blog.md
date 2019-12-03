---
layout: blog
title: Blog
date:   2019-12-02
author: Cameron Taylor
permalink: /blog/
---

Blog | [My Personal Website](https://cameronntaylor.github.io/)

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <div class="entry">
        {{ post.excerpt }}
      </div>
    </article>
  {% endfor %}
</div>

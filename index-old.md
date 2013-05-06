---
layout: page
title: Hello World!
tagline: Supporting tagline
---

{% include JB/setup %}

 <div class="row">

    <!-- Main Blog Content -->
    <div class="large-9 columns" role="content">

    {% for post in site.posts %}

      <article>

        <h3><a href="#">{{ post.title }}</a></h3>
        <h6>Written by <a href="#">John Smith</a> on August 12, 2012.</h6>

        <div class="row">
          {{ post.content }}

      </article>

      <hr />
    
    {% endfor %}
    
    </div>
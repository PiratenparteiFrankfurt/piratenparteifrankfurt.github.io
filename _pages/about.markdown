---
# This file is licensed under the MIT License (MIT) available on
# http://opensource.org/licenses/MIT.

layout: base
title: About
permalink: /about
id: about
---
<link rel="alternate" type="application/atom+xml" href="/en/rss/blog.xml" title="Bitcoin.org Site Blog">

<div class="home">

  <div class="hero">
    <div class="container hero-container">
      <h1 class="page-heading">Bitcoin.org Site Blog</h1>
      <p class="summary">Discover what's new on Bitcoin.org or
        <a type="application/atom+xml" href="/en/rss/blog.xml">subscribe to the RSS feed</a>
      </p>
    </div>
  </div>

  <div class="blog">
    <div class="container">
      <ul class="post-list clearfix">
        {% for post in site.posts %}
        <li class="post">
          <div class="post-inner">
            <p class="post-date">{{ post.date | date: "%b %-d, %Y" }}</p>
            <p class="post-name">{{ post.title }}</p>
            <p class="post-description">
              <!-- Event description -->
            </p>
            <a class="button btn-bright" href="{{ post.url | remove: '.html' }}">Weiterlesen</a>
          </div>
        </li>
        {% endfor %}
      </ul>
      <div class="btn-container">
        <button class="button btn-dark" id="loadMore">Mehr Beiträge laden</button>
      </div>
    </div>
  </div>

</div>

<script src="/js/loadMorePosts.js"></script>

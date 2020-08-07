---
layout: default
title: Home
---
# AI for Social Good

**The webpage for this workshop has moved. The IJCAI 2020 (January 2021) workshop website is <a href="https://crcs.seas.harvard.edu/event/ai-social-good-workshop-0?admin_panel=1&month=2020-08&type=month">here.</a>**

**The summer 2020 workshop website is <a href="https://crcs.seas.harvard.edu/event/ai-social-good-workshop?delta=0">here.</a>**

<div class="posts">
  {% for post in paginator.posts %}
  <div class="post">
    <h1 class="post-title">
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    {{ post.content }}
  </div>
  {% endfor %}
</div>



---
layout: page
title: Invited Speakers
---

### Sharad Goel
Assistant Professor, Department of Management Science & Engineering, Stanford University

### Hongying Lilian Tang
Senior Lecturer, Department of Computer Science, University of Surrey

### Stefano Ermon
Assistant Professor, Department of Computer Science, Stanford University



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



---
layout: page
title: Organization
---

## Organizing Committee

* Arpita Biswas (Indian Institute of Science)
* Eric Horvitz (Microsoft Research)
* Andrew Perrault (Harvard University)
* Sekou Remny (IBM Research Africa)
* Sofia Segkouli (Information Technologies Institute, Thessaloniki, Greece)
* Andreas Theodorou (Umeå University)
* Bryan Wilder (Harvard University)




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



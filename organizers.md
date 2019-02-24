---
layout: page
title: Organizing Committee
---

* Nika Haghtalab (Microsoft Research, New England)
* Eric Horvitz (Microsoft Research, Redmond)
* Ezinne Nwankwo (Duke University)
* Andreas Theodorou (Umeå University)
* Bryan Wilder (University of Southern California)


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



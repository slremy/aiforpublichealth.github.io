---
layout: page
title: Invited Speakers
---

* Joanna Bryson (Hertie School of Governance)
* Oisin Mac Aodha (School of Informatics, University of Edinburgh)
* Vukosi Marivate (Department of Computer Science, University of Pretoria)
* Ziad Obermeyer (UC Berkeley School of Public Health)
* Danielle Wood (MIT Media Lab)

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



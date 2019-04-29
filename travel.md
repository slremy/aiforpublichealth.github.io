---
layout: page
title: Travel Awards
---

We have a limited amount of funding available to help cover travel costs for workshop participants. Participants who expect to need travel support should apply to the IJCAI [travel grants](https://www.ijcai19.org/travel-grants.html) and, if applicable [student volunteer](https://www.ijcai19.org/call-for-volunteers.html) program (once those applications become available). Our travel awards will supplement this funding. Awards will be made based on participant need and relevance to the workshop, with preference given to individuals who have submitted a workshop paper.         

**Application Deadline**: May 12, 2019. 
**Process**:Please email Ezinne Nwankwo (enwankwo17@gmail.com) and Bryan Wilder (bryan.wilder0@gmail.com) by the deadline with the subject line "IJCAI workshop travel award". Include your name, affiliation, and whether you have or plan to submit a workshop paper. We will be in contact to request additional information as needed. 


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



---
layout: page
title: Organization
---

# Organizing Committee

* Nika Haghtalab (Microsoft Research, New England)
* Eric Horvitz (Microsoft Research, Redmond)
* Ezinne Nwankwo (Duke University)
* Andreas Theodorou (Umeå University)
* Bryan Wilder (University of Southern California)

# Program Committee

* Andrea Aler Tubella (Umeå University)
* Elizabeth Bondi (University of Southern California)
* Frank Cheng (University of Michigan Ann Arbor)
* Amanda Coston (Carnegie Mellon University)
* Travis Dick (Carnegie Mellon University)
* Virginia Dignum (Delft University of Technology)
* Aaron Ferber (University of Southern California)
* Benjamin Fish (Microsoft)
* Amrita Gupta (Georgia Institute of Technology)
* Timotheus Kampik (Umeå University)
* Duncan Mcelfresh (University of Maryland)
* Benjamin Otieno (Kibabii University)
* Han-Ching Ou (University of Southern California)
* Andrew Perrault (University of Southern California)
* David Robinson (Georgia Institute of Technology)
* Kris Sankaran (Mila)
* Teresa Scantamburlo (Università Ca'Foscari)
* Candice Schumann (University of Maryland)
* Zheyuan Ryan Shi (Carnegie Mellon University)
* Ana-Andreea Stoica (Columbia University)
* Kai Wang (University of Southern California)
* Holly Wilson (University of Bath)
* Robert Wortham (University of Bath)
* Amulya Yadav (Pennsylvania State University)
* Angela Zhou (Cornell University and Cornell Tech)


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



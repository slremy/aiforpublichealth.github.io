---
layout: page
title: Program
---

**9-9:15: Opening**

**9:15-9:30 Contributed talk**

  Nixie Lesmana, Xuan Zhang and Xiaohui Bei. Balancing Efficiency and Fairness in On-Demand Ridesourcing.	
		
**9:30-10:00: Poster spotlights (Submission numbers 1-24)**

**10:00-10:30: Poster session/break**

**10:30-11:00 Contributed talks**

  Boli Fang, Miao Jiang, Jerry Shen, Pei-Yi Cheng and Manju Chivukula. Food Fairness: An Artificial Intelligence Perspective for SNAP Allocation.
  
  Duncan Mcelfresh, Christian Kroer, Sergey Pupyrev, Eric Sodomka and John Dickerson. Matching Algorithms for Blood Donation.

**11:00-11:45: Invited talk: Sharad Goel**

**11:45-12:30: Contributed talks**

Sunayana Rane. A sparse, data-efficient ECG representation is predictive of myocardial infarction without expert knowledge.

Muhammed Razzak and Kris Sankaran. Interactive Segmentation for Disaster Relief Mapping.

Debarun Bhattacharjya, Karthikeyan Shanmugam, Tian Gao, Nicholas Mattei and Kush Varshney. Event-Driven Continuous Time Bayesian Networks: An Application in Modeling Progression out of Poverty through Integrated Social Services.	
	
**12:30-2pm Lunch**

**2-2:45: Invited talk: Lilian Tang**

**2:45-3:00: Contributed talk**

Yiwen Yuan, Kimberly Lo, Zheyuan Ryan Shi, Leah Lizarondo and Fei Fang. Efficiency and Fairness of Food Rescue Platforms: An Initial Study.

**3:00-3:30: Poster spotlights (Submission numbers 25-43)**

**3:30-4:00: Poster session/break**

**4:00-4:30pm: Contributed talks**

Dereje Yohannes Ashenafi, Zelalem Mihret, Alemenew Shiferaw. Web based Expert system for the prevention, diagnosis and treatment of Malaria using two Ethiopian local languages (Amharic & Afan Oromo).

Andrew Perrault, Bryan Wilder, Eric Ewing, Aditya Mate, Bistra Dilkina and Milind Tambe. Decision-Focused Learning of Adversary Behavior in Security Games.
	
**4:30-5:15: Invited talk: Stefano Ermon**

**5:15-5:30pm Closing** 

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



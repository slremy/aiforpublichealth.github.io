---
layout: page
title: Invited Speakers
---

## Susan Murphy

Susan Murphy is Professor of Statistics at Harvard University, Radcliffe Alumnae Professor at the Radcliffe Institute, Harvard University, and Professor of Computer Science at the Harvard John A. Paulson School of Engineering and Applied Sciences.  Her lab works on clinical trial designs and online learning algorithms for developing personalized mobile health interventions.   She is a 2013 MacArthur Fellow, a member of the National Academy of Sciences and the National Academy of Medicine, both of the US National Academies. 

## Nuria Oliver

Nuria Oliver is Chief Data Scientist at Data-Pop Alliance, Chief Scientific Advisor at the Vodafone Institute, co-founder and vice-president of ELLIS (The European Laboratory for Learning and Intelligent Systems) and co-founder of the Alicante ELLIS Unit, devoted to research on "Human(ity)-centric Artificial Intelligence".  She is a Telecommunications Engineer from the Universidad Politécnica de Madrid and holds a PhD in Artificial Intelligence from the Massachusetts Institute of Technology (MIT).  In March 2020, she was named Commissioner for the President of the Valencian Region on AI Strategy and Data Science to fight Covid-19. Since then, she has led a team of with 20+ data scientists. She is an independent member of the Board of Directors at Bankia.

## Suvrit Sra

Suvrit Sra is the Esther and Harold E. Edgerton (1927) Career Development Associate Professor of Electrical Engineering and Computer Science at MIT and a core faculty member in the MIT Institute for Data, Systems, and Society. He is also Chief AI Officer and co-founder at macro-eyes, a startup focused on global health. macro-eyes developed a vaccine forecasting tool that reduced vaccine wastage by 96 percent across three regions of Tanzania  and a patient scheduling platform which has analyzed over 6 million hospital appointments and reduced wait times by more than 75 percent at one of the largest heart hospitals in the U.S. Suvrit’s work has won several awards at machine learning conferences, as well as the 2011 “SIAM Outstanding Paper” award, faculty research awards from Criteo and Amazon, and an NSF CAREER award. He founded the OPT (Optimization for Machine Learning) series of workshops at the NIPS conference, which he has co-chaired since 2008 and was an area chair for NeuRIPS 2019.

## Aisha Walcott
Aisha Walcott is a research scientist and manager at IBM Research Africa - Nairobi, Kenya. She leads a team of research scientists and engineers in the development of novel innovations in the Future of Health and Climate. She and her team leverage AI, Blockchain, and other technologies to create solutions to transform Health Systems, provide new tools for Population Health, and develop systems to support Water Access and Management particularly for emerging countries. When Aisha joined the IBM Research Africa lab, she led the research efforts to improve mobility and transportation in developing cities. She and her team developed innovative intelligent transportation systems data capture methods and analytical tools, to provide computational understanding about the local driving and infrastructure context. Aisha earned her PhD in the Electrical Engineering and Computer Science Department at MIT.


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



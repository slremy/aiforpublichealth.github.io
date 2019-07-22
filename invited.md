---
layout: page
title: Invited Speakers
---

### Sharad Goel
Assistant Professor, Department of Management Science & Engineering, Stanford University

#### The Measure and Mismeasure of Fairness: A Critical Review of Fair Machine Learning

The nascent field of fair machine learning aims to ensure that decisions guided by algorithms are equitable. Over the last several years, three formal definitions of fairness have gained prominence: (1) anti-classification, meaning that protected attributes -- like race, gender, and their proxies -- are not explicitly used to make decisions; (2) classification parity, meaning that common measures of predictive performance (e.g., false positive and false negative rates) are equal across groups defined by the protected attributes; and (3) calibration, meaning that conditional on risk estimates, outcomes are independent of protected attributes. 

I'll show that all three of these fairness definitions suffer from significant statistical limitations. Requiring anti-classification or classification parity can, perversely, harm the very groups they were designed to protect; and calibration, though generally desirable, provides little guarantee that decisions are equitable. In contrast to these formal fairness criteria, I'll argue that it is often preferable to treat similarly risky people similarly, based on the most statistically accurate estimates of risk that one can produce. Such a strategy, while not universally applicable, often aligns well with policy objectives; notably, this strategy will typically violate both anti-classification and classification parity. In practice, it requires significant effort to construct suitable risk estimates. One must carefully define and measure the targets of prediction to avoid retrenching biases in the data. But, importantly, one cannot generally address these difficulties by requiring that algorithms satisfy popular mathematical formalizations of fairness. By highlighting these challenges in the foundation of fair machine learning, we hope to help researchers and practitioners productively advance the area.

Paper: https://5harad.com/papers/fair-ml.pdf

Sharad Goel is an Assistant Professor at Stanford University in the Department of Management Science & Engineering, and is the founder and director of the Stanford Computational Policy Lab. He also holds courtesy appointments in Computer Science, Sociology, and the Law School. In his research, Sharad looks at public policy through the lens of computer science, bringing a new, computational perspective to a diverse range of contemporary social issues, including criminal justice reform, electoral integrity, and online education. Before joining the Stanford faculty, Sharad completed a Ph.D. in Applied Mathematics at Cornell University, and worked as a Senior Researcher at Microsoft in New York City.



### Hongying Lilian Tang
Senior Lecturer, Department of Computer Science, University of Surrey

#### Context and Evidence-based Deep Learning for Medicine

Patients’ data are dynamic and complex, varying across pathological conditions, ethnic origins, doctors’ experience, healthcare policies, to name a few. While developing an automated software for supporting clinical services and better patient’s care, there are significant challenges in technical areas for data acquisition/analysis/management and communication across all stakeholders. It is necessary to understand how a machine learning approach will fit into, or disrupt, the existing healthcare pathways. 

This talk will walk through a few applications of deep learning in the medical domain that take advantage of clinical data in natural language texts, images and videos for the assessment of disease conditions, diagnosis and treatment management of patients as well as training for skilled doctors. It will then look into how to address the issues that arise when only noisy, limited or unlabelled data are mostly available when engineering such tools, with an effort to bridge the gaps between the ways of how machines and clinicians deal with data. Approaches on deriving clinically relevant evidence for supporting the prediction from learning algorithms and how context plays a key role in such process will be explored.

Dr Lilian Tang received her PhD from the University of Cambridge in medical informatics and currently is working at the University of Surrey as a Reader in AI. She is interested in applying machine learning to image and natural language text analysis, with a particular focus on the medical domain. Over the last decade, she has been working with a number of NHS hospitals, as well as hospitals in Europe and Mid and Far-east Asia, on a wide range of projects including: the development of automated tracking of fine movements of surgical instruments in eye and other microsurgeries, for objective dexterity analysis; digital retinal image analysis to understand various eye and systemic conditions; time-lapse bacterial cell image analysis for understanding mycobacterial persistence; and natural language processing on medical records. A key feature of her work is that she always uses the AI systems to gain a deeper understanding of their problem domain, and does not simply aim to replicate human-level performance.



### Stefano Ermon
Assistant Professor, Department of Computer Science, Stanford University

#### Measuring Economic Development from Space

Recent technological developments are creating new spatio-temporal data streams that contain a wealth of information relevant to sustainable development goals. Modern AI techniques have the potential to yield accurate, inexpensive, and highly scalable models to inform research and policy. A key challenge, however, is the 
lack of large quantities of labeled data that often characterize successful machine learning applications. In this talk, I will present new approaches for learning useful spatio-temporal models in contexts where labeled training data is scarce or not available at all. I will show applications to predict and map poverty in developing countries, monitor  agricultural productivity and food security outcomes, and map infrastructure access in Africa. Our methods can reliably predict economic well-being using only high-resolution satellite imagery. Because images are passively collected in every corner of the world, our methods can provide timely and accurate measurements in a very scalable end economic way, and could revolutionize efforts towards global poverty eradication.

Stefano Ermon is an Assistant Professor of Computer Science in the CS Department at Stanford University, where he is affiliated with the Artificial Intelligence Laboratory, and a fellow of the Woods Institute for the Environment. His research is centered on techniques for probabilistic modeling of data, inference, and optimization, and is motivated by a range of applications, in particular ones in the emerging field of computational sustainability. He has won several awards, including four Best Paper Awards (AAAI, UAI and CP), a NSF Career Award, ONR and AFOSR Young Investigator Awards, a Sony Faculty Innovation Award, an AWS Machine Learning Award, a Hellman Faculty Fellowship, Microsoft Research Fellowship, and the IJCAI Computers and Thought Award. Stefano earned his Ph.D. in Computer Science at Cornell University in 2015.


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



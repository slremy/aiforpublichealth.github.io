---
layout: page
title: Accepted Papers
---

* Takayuki Ito, Shota Suzuki, Naoko Yamaguchi, Tomohiro Nishida, Kentaro Hiraishi and Kai Yoshino. Towards Smarter Democracy: An Agent-based Large-scale Discussion Support System.
* Elizabeth Bondi, Hoon Oh, Haifeng Xu, Fei Fang, Bistra Dilkina and Milind Tambe. Protecting Animals From Poaching: Using Uncertain Real-Time Information in Signaling Games.
* Sonam Damani, Nitya Raviprakash, Ankush Chatterjee, Meghana Joshi and Puneet Agrawal. Using AI for Economic Upliftment of Handicraft Industry.
* Dereje Ashenafi, Zelalem Mihret, Alemenew Shiferaw. Web based Expert system for the prevention, diagnosis and treatment of Malaria using two Ethiopian local languages (Amharic & Afan Oromo).
* Haris Aziz, Serge Gaspers and Zhaohong Sun. Mechanism Design for School Choice with Soft Diversity Constraints.
* Santosh Misra and Dibu Philip. Predictive and prescriptive governance - improved delivery of government services.
* Kalkidan Gezahegn and Sudeshna Chakraborty. Automatic Target Recognition and Classification from Synthetic Aperture Radar Imagery using Multi-Stream Convolution Neural Network.
* Nixie Lesmana, Xuan Zhang and Xiaohui Bei. Balancing Efficiency and Fairness in On-Demand Ridesourcing.
* Paul Weng. Fairness in Decision Support Systems and Autonomous Systems.
* Kai Wang, Aditya Mate, Bryan Wilder, Andrew Perrault and Milind Tambe. Using Graph Convolutional Networks to Learn Interdiction Games.
* Hadi Hosseini, Sujoy Sikdar, Rohit Vaish, Jun Wang and Lirong Xia. Fair Division through Information Withholding.
* Haibin Wang, Sujoy Sikdar, Xiaoxi Guo, Lirong Xia, Yongzhi Cao and Hanpin Wang. Multi-type Resource Allocation with Partial Preferences.
* Andrew Perrault, Bryan Wilder, Eric Ewing, Aditya Mate, Bistra Dilkina and Milind Tambe. Decision-Focused Learning of Adversary Behavior in Security Games.
* Marvin Oeben, Jeroen Goudsmit and Elena Marchiori. Prerequisites and AI challenges for model-based Anti-Money Laundering.
* Sunayana Rane. A sparse, data-efficient ECG representation is predictive of myocardial infarction without expert knowledge.
* Mor Vered, Frank Dignum and Timothy Miller. Let's Make It Personal : A Challenge in Personalizing Medical Inter-Human Communication.
* Shengda Luo, Alex Leung and Xingzhao Qiu. Safety for Public Transportation: Driver Behavior Analytics for Road Safety with Boosting.
* Dhananjay Nahata, Prateek Dusad and Harish Mulchandani. Semantic Segmentation Based Earthquake Damage Assessment of Built Environment.
* Anton Kolonin, Ben Goertzel, Cassio Pennachin, Deborah Duong, Marco Argentieri, Matt Ikle and Nejc Znidar. A Liquid Democracy System for Human-Computer Societies.
* Muhammed Razzak and Kris Sankaran. Interactive Segmentation for Disaster Relief Mapping.
* Debarun Bhattacharjya, Karthikeyan Shanmugam, Tian Gao, Nicholas Matteiand Kush Varshney. Event-Driven Continuous Time Bayesian Networks: An Application in Modeling Progression out of Poverty through Integrated Social Services.
* Tiago Pinto and Zita Vale. An adaptive system for decision support of electricity markets negotiations.
* Daniel Mutembesa. Incentive allocation function for mobile community sensing with smallholder farmers in a developing nation..
* Yiwen Yuan, Kimberly Lo, Zheyuan Ryan Shi, Leah Lizarondo and Fei Fang. Efficiency and Fairness of Food Rescue Platforms: An Initial Study.
* Ryoji Wada, Kentaro Yahiro, Taiki Todo and Makoto Yokoo. Achieving a Fair Matching under Partial Information.
* Mirka Snyder Caron and Abhishek Gupta. The Social Contract for AI.
* Kinzang Chhogyal, Abhaya Nayak, Aditya Ghose, Mehmet Orgun and Hoa Dam. On Conforming and Conflicting Values.
* Boli Fang, Miao Jiang, Jerry Shen, Pei-Yi Cheng and Manju Chivukula. Achieving Fairness in Determining Medicaid Eligibility through Fairgroup Construction.
* Deborah Duong, Anton Kolonin, Ben Goertzel, Cassio Pennachin, Matt Ikle, Nejc Znidar and Marco Argentieri. A Reputation System for Market Security and Equity.
* Duncan Mcelfresh, Christian Kroer, Sergey Pupyrev, Eric Sodomka and John Dickerson. Matching Algorithms for Blood Donation.
* Jackson Killian, Bryan Wilder, Amit Sharma, Vinod Choudhary, Daksha Shah, Bistra Dilkina and Milind Tambe. A Framework for Machine Learning in Digital-Based Tuberculosis Treatment.
* Boli Fang, Miao Jiang, Jerry Shen, Pei-Yi Cheng and Manju Chivukula. Food Fairness: An Artificial Intelligence Perspective for SNAP Allocation.


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

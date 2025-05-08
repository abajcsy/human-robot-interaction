---
layout: home
title: Home
permalink: /:path/
seo:
  type: Course
  name: Human Robot Interaction
---

# Human Robot Interaction
Fall 2025. 16-867. Tuesday / Thursday 11:00am-12:20pm.

![Image](/assets/images/front-fig.png)

## Announcements 
<!-- Displays All Annoucements -->
<!-- {% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %} -->

<!-- Displays Most Recent Annoucement -->
{% assign announcement = site.announcements | reverse | first %}
{{ announcement }}

## Course Overview 
Robot interaction with people is inevitable: human engineers iteratively tune robot policies, autonomous cars navigate through crowded cities, construction workers teleoperate drones for building inspections, and assistive robots help end-users with daily living tasks. 

In this graduate class, we will formalize such human-robot interaction (HRI) problems algorithmically. We will build the mathematical foundations for modeling human-robot interaction across robots and tasks, enable robots to understand human intent and predict human behavior, and study how robot learning changes in the presence of human feedback. The approaches covered will draw upon a variety of disciplines and tools such as sequential decision-making, cognitive science, Bayesian inference, and modern machine learning. Throughout the class, there will also be several guest lectures from experts in the field. Students will practice essential research skills including reviewing papers, writing project proposals, and technical communication.

In summary, in this class you will learn how to:
* 👩‍🔬  Mathematically model HRI
* 🧠  Predict human behavior & infer intent
* 🤝  Robot learning from human feedback 
* 🙌  and more!


### Prerequisites
The course is open to graduate students and advanced undergraduates. There are no official prerequisites but we expect familiarity with robotics and related AI topics (e.g., sequential decision-making / planning, basic machine learning); willingness to conduct a significant final project outside of class time; willingness to read scientific papers and engage in in-class discussions; willingness to conduct in-class presentations about scientific literature. Experience with high-level programming languages like Python are also strongly encouraged. 


## Schedule (Tentative) 

{% for module in site.modules %}
{{ module }}
{% endfor %}


## Instructor

<figure style="display: inline-flex;">

<figure>
<img src="/human-robot-interaction/assets/images/avb.png" alt="Avatar" style="width:200px; height:auto; object-fit: cover; border-radius:50%; padding:20px;">
<figcaption style="text-align: center;"><a href="https://www.cs.cmu.edu/~abajcsy/"><button type="button" name="button" class="btn">Andrea Bajcsy</button>
</a></figcaption>
</figure>

</figure>

## Teaching Assistant 

<figure style="display: inline-flex;">

<figure>
<img src="/human-robot-interaction/assets/images/yw.jpeg" alt="Avatar" style="width:200px; height:auto; object-fit: cover; border-radius:50%; padding:20px;">
<figcaption style="text-align: center;"><a href="https://yilin-wu98.github.io/"><button type="button" name="button" class="btn">Yilin Wu</button>
</a></figcaption>
</figure>

</figure>



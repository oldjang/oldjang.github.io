---
permalink: /
title: "Mengxu JIANG"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span id="about"></span>

I am a Ph.D. Candidate in the [Database Group](https://dbgroup.se.cuhk.edu.hk/) at [The Chinese University of Hong Kong](https://www.cuhk.edu.hk/), advised by [Prof. Sibo Wang](https://www1.se.cuhk.edu.hk/~swang/).

My research focuses on efficient indexing and query processing for high-dimensional vector data, especially approximate nearest neighbor search, filtered vector search, and dynamic indexing.

Before joining CUHK, I received my B.Sc. in Computer Science and Technology from Wuhan University.

<span id="publications"></span>

Publications
======

{% for post in site.publications reversed %}
  {% if post.category == "conferences" %}
    {% include publication-single.html %}
  {% endif %}
{% endfor %}

<span id="experience"></span>

Experience
======

* **Microsoft Research Asia (MSRA), Beijing, China**. Research Intern, Jul. 2026 -- Present.

* **Alibaba Cloud, Hangzhou, China**. Research Intern, Jul. 2025 -- Dec. 2025.

* **The Chinese University of Hong Kong, Hong Kong SAR**. Research Assistant, Aug. 2022 -- Aug. 2023.

Research Interests
======

* Approximate nearest neighbor search
* Filtered and dynamic vector indexing

<span id="awards"></span>

Selected Awards
======

* Gold Medal, 2020 ICPC Asia Shenyang Regional Contest
* Gold Medal, 2019 China Collegiate Programming Contest, Xiamen Site
* Gold Medal, 2018 ACM-ICPC Asia Qingdao Regional Contest
* Bronze Medal, 34th China National Olympiad in Informatics (NOI)

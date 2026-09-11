---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

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

* **Research Intern**, Microsoft Research Asia (MSRA), System Research Group, Jul. 2026 -- Present  
  Selected for the Honorary Scholars Talent Program. Exploring memory systems for long-horizon AI agents.

* **Research Intern**, Alibaba Cloud, ADBPG Team, Jul. 2025 -- Dec. 2025  
  Integrated NVIDIA's GPU ANNS library cuVS into ADBPG, a distributed database based on PostgreSQL. Developed a GPU resource management server using PostgreSQL's Background Worker and Unix domain socket communication for efficient GPU resource sharing across processes.

* **Research Assistant**, The Chinese University of Hong Kong, Aug. 2022 -- Aug. 2023  
  Contributed to the research and implementation of an efficient dynamic weighted set sampling algorithm. The work was published in VLDB 2023.

Research Interests
======

* Approximate nearest neighbor search
* Filtered vector search
* Dynamic indexing
* High-dimensional vector data management

<span id="awards"></span>

Selected Awards
======

* Gold Medal, 2020 ICPC Asia Shenyang Regional Contest
* Gold Medal, 2019 China Collegiate Programming Contest, Xiamen Site
* Gold Medal, 2018 ACM-ICPC Asia Qingdao Regional Contest
* Bronze Medal, 34th China National Olympiad in Informatics (NOI)

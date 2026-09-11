---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **The Chinese University of Hong Kong**, Ph.D. Candidate in the Database Group, Aug. 2023 -- Present  
  Advisor: [Prof. Sibo Wang](https://www1.se.cuhk.edu.hk/~swang/)
* **Wuhan University**, B.Sc. in Computer Science and Technology, Sep. 2018 -- Jun. 2022

Work experience
======
* **Research Intern**, Microsoft Research Asia (MSRA), System Research Group, Jul. 2026 -- Present
  * Selected for the Honorary Scholars Talent Program.
  * Exploring memory systems for long-horizon AI agents.
* **Research Intern**, Alibaba Cloud, ADBPG Team, Jul. 2025 -- Dec. 2025
  * Integrated NVIDIA's GPU ANNS library cuVS into ADBPG, a distributed database based on PostgreSQL.
  * Developed a GPU resource management server using PostgreSQL's Background Worker and Unix domain socket communication for efficient GPU resource sharing across processes.
* **Research Assistant**, The Chinese University of Hong Kong, Aug. 2022 -- Aug. 2023
  * Contributed to the research and implementation of an efficient dynamic weighted set sampling algorithm, published in VLDB 2023.
  
Research interests
======
* Efficient indexing and query processing for high-dimensional vector data
* Approximate nearest neighbor search
* Filtered vector search
* Dynamic indexing

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
Selected honors and awards
======
* Gold Medal, 2020 ICPC Asia Shenyang Regional Contest
* Gold Medal, 2019 China Collegiate Programming Contest, Xiamen Site
* Gold Medal, 2018 ACM-ICPC Asia Qingdao Regional Contest
* Bronze Medal, 34th China National Olympiad in Informatics (NOI)

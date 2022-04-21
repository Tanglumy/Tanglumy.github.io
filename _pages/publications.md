---
layout: page
permalink: /publications/
title: publications
description: 
years: [2021]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
<!-- 
@article{einstein1905molekularkinetischen
  title={Readability Controlled Open-domain QA for COVID-19},
  author={Zhehan Qu, Lumingyuan Tang, Xiao Liu, Gary Becigeul},
  abstract={The continuous spread of COVID-19 these days has been calling for a way to provide instant and readable knowledge for researchers, medical workers and the general public. Recent works on COVID related question answering (QA) systems have leveraged retrievalbased structures and yielded promising results, yet sometimes their answers could become unreadable for most users due to the highly technical nature of their knowledge source. We propose RC-RAG for Readability Controlled Retrieval Augmented Generation, an open-domain question-answering system on COVID related topics, which is capable of generating answers of a chosen readability score given a COVID-related question. Our model is proved to generate answers of different readability levels, and could meet the requirements of people with different levels of education. We hope our system will be able to aid researchers and the general public to go through this tough time together.},
  journal={Phys. Rev.,},
  volume={47},
  issue={10},
  pages={777--780},
  numpages={0},
  year={2021},
  month={May},
  publisher=aps,
  doi={10.1103/PhysRev.47.777},
  url={http://link.aps.org/doi/10.1103/PhysRev.47.777},
  html={https://journals.aps.org/pr/abstract/10.1103/PhysRev.47.777},
<!--   
  selected={true}
} --> 

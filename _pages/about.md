---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="kar-container">
  <p class="kar-intro"> Welcome! I am a GIScientist and transportation geographer researching the complex interactions between human mobility, environment, safety, and health. Currently, I serve as an Assistant Professor in the Department of Geography and Geoinformation Science at George Mason University. I completed my Ph.D. in Geography at The Ohio State University in 2023, my Master's in Geography and GIS at the University of Utah in 2019, and Bachelor's in Urban and Regional Planning from the Bangladesh University of Engineering and Technology (BUET) in 2015. </p>
  <p class="kar-intro"> My research lies at the intersection of GIScience, transportation geography, cognitive and behavioral geography, and health and safety. I am specifically interested in modelling and understanding how urban environments and the human experiences around them shape urban mobility, as well as their safety and health outcomes across diverse population groups. My work integrates geospatial artificial intelligence (GeoAI), spatiotemporal modeling, network analytics, and citizen science to advance data-driven, human-centered solutions for safer, healthier, and more inclusive transportation environments.</p>

<div class="kar-section-title">My current research answers three main questions</div>

 <!-- Card 1 -->
  <div class="kar-card kar-card--blue">
    <div class="kar-card__icon">
      <img src="images/research_q1.png" alt="AI icon">
    </div>
    <div class="kar-card__text">
      <b>1. How can we combine multi-sensory data, large language models, and agentic AI to better characterize multimodal transportation environments and human experiences?</b>
    </div>
  </div>

  <!-- Card 2 -->
  <div class="kar-card kar-card--green">
    <div class="kar-card__icon">
      <img src="images/research_q2.jpeg" alt="Risk icon">
    </div>
    <div class="kar-card__text">
      <b>2. How can we leverage spatio-temporal AI models to detect and predict actual and perceived road risks, and support safe infrastructure design, planning, and decision-making?</b>
    </div>
  </div>

  <!-- Card 3 -->
  <div class="kar-card kar-card--orange">
    <div class="kar-card__icon">
      <img src="images/research_q3.jpg" alt="Health icon">
    </div>
    <div class="kar-card__text">
      <b>3. How can we integrate space-time accessibility measures, spatial interaction models, and geostatistics to reveal spatio-social barriers of healthcare access and travel?</b>
    </div>
  </div>


<p class="kar-footer-text"> My work has been published in several high-impact, peer-reviewed journals, including <i>Annals of the American Association of Geographers (AAG), Computers, Environment and Urban Systems, Transportation Research Part D, Applied Geography, Journal of Transport Geography, Transportation Research Record (TRR), Risk Analysis,</i> and <i>Atmospheric Environment</i>. I received several awards for my work, including <i>the Postdoc Idea Award from the NCH Abigail Wexner Research Institute, the E. Willard and Ruby S. Miller Scholarship from The Ohio State University, the Student Dissertation Award from the Sustainability Institute at The Ohio State University,</i> and <i>the Prime Minister Gold Medal from the University Grants Commission of Bangladesh</i>.</p>

<div class="kar-section-title">Recent updates</div>

{% for update in site.data.updates %}
<details>
<summary><b>{{ update.date }}</b></summary>
<p align="justify">{{ update.body }}</p>
{% if update.images %}
  <p>
    {% for img in update.images %}
    <img src="{{ img }}" style="border:0" width="45%">
    {% endfor %}
  </p>
{% endif %}
</details>
{% endfor %}

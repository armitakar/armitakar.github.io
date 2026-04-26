---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  gap: 24px;
}

.project-link {
  text-decoration: none;
  color: inherit;
}

.project-card {
  border: 1px solid #eee;
  border-radius: 14px;
  padding: 18px;
  background: #fff;
  box-shadow: 0 4px 12px rgba(0,0,0,0.05);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  height: 100%;
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 22px rgba(0,0,0,0.08);
}

.project-title {
  font-size: 16px;
  font-weight: 600;
  margin-bottom: 8px;
}

.project-desc {
  font-size: 14px;
  color: #444;
  text-align: justify;
}

.project-img {
  width: 100%;
  border-radius: 8px;
  margin-top: 12px;
}

.project-caption {
  font-size: 12px;
  color: #777;
  text-align: center;
  margin-top: 6px;
}
</style>

<div class="project-grid">

  <!-- Project 1 -->
  <a href="#" class="project-link">
    <div class="project-card">
      <div class="project-title">
        Interrelationship between pedestrian streetscape, perceptions, and willingness
      </div>
      <div class="project-desc">
        This research quantifies micro-level pedestrian streetscape features using Vision Language models and examines both mediation pathways and predictive relationships among pedestrian streetscape, safety perceptions, and walking willingness using SEM, GPBoost, and SHAP analysis. Findings highlight the importance of features such as curb ramps, traffic controls, and green spaces in shaping perceived safety, which in turn drives people’s willingness to walk — offering actionable insights for encouraging walking behavior.
      </div>
      <img src="/images/TRB_Poster_2026.jpg" class="project-img">
      <div class="project-caption">
        Presented at TRB 2026
      </div>
    </div>
  </a>

  <!-- Project 2 -->
  <a href="#" class="project-link">
    <div class="project-card">
      <div class="project-title">
        Healthcare Deserts in Virginia
      </div>
      <div class="project-desc">
        This study examines how healthcare deserts and their rural–urban and socioeconomic drivers vary across spatiotemporal scales and healthcare provider types. Using the state of Virginia as a case study, the work emphasizes the need for high-resolution spatial analysis to accurately locate healthcare disadvantaged areas.
      </div>
      <img src="/images/GMU_Healthcare_Deserts_TRB presentation.jpg" class="project-img">
      <div class="project-caption">
        County vs. tract-level patterns
      </div>
    </div>
  </a>

  <!-- Project 3 -->
  <a href="#" class="project-link">
    <div class="project-card">
      <div class="project-title">
        Determinants of Prenatal Care Travel
      </div>
      <div class="project-desc">
        Proximity enables interaction, but what else influences where people go? Using 19.8 million prenatal trips to maternal healthcare facilities across Florida (2016-2022), constructed from patient hospital electronic visitation records, we examine how spatial, socioeconomic, and facility characteristics influence travel. We estimate a negative binomial model of trip counts incorporating origin-, destination- and flow-based predictors. While distance remains a dominant deterrent, its influence is conditioned by rurality, facility capacity, and community health context. These patterns underscore that prenatal maternal travel reflects broader contextual factors beyond geographic distance.
      </div>
      <img src="/images/Florida_OD_flow_map.jpg" class="project-img">
      <div class="project-caption">
        Prenatal OD flows in Florida
      </div>
    </div>
  </a>

  <!-- Project 4 -->
  <a href="#" class="project-link">
    <div class="project-card">
      <div class="project-title">
        Inclusive Accessibility
      </div>
      <div class="project-desc">
        Inclusive Accessibility: A Socially-Sensitive Approach of Incorporating Perceptions into Space-time Accessibility Measures</b> <p align="justify">My doctoral dissertation focuses on pioneering a novel concept and measure known as inclusive accessibility. This approach integrates people’s diverse travel choices and experiences into advancing space-time accessibility models. I posit this measure as a more realistic and socially aware representation of accessibility, as it distinguishes between the geographic spaces that are physically and perceptually accessible to individuals and social groups. My PhD dissertation also demonstrates application of inclusive accessibility approach in tailoring transportation infrastructure interventions specific to marginalized communities.
      </div>
      <img src="/images/walking impedance.png" class="project-img">
      <img src="/images/Inclusive access.png" class="project-img">
      <div class="project-caption">
        Perception-driven accessibility differences
      </div>
    </div>
  </a>

</div>


<b>Post Doctoral Research Scientist.</b> (August 2023 - July 2024)
<br>Center for Injury Research and Policy, Abigail Wexner Research Institute at Nationwide Children’s Hospital (AWRINCH), OH, United States

Project title: <i>Intervention to improve driving practices among high-risk teen drivers</i>
<br>Supervisor/PI: Ginger Yang
<br>Funded by: National Institutes of Health (NIH) - The Eunice Kennedy Shriver National Institute of Child Health and Human Development (NICHD)

<b>Graduate Research Assistant.</b> (August 2022 - August 2023)
<br>Center for Urban and Regional Analysis, The Ohio State University, OH, United States

Project title: <i>Built environment influences reckless driving behavior</i>
<br>Supervisor/PI: Harvey J. Miller and Ginger Yang (Nationwide Children’s Hospital, Columbus, Ohio)
<br>Funded by: Translational Data Analytics Institute at The OSU

<b>Graduate Research Assistant.</b>	(May 2021 – August 2022)
<br>Department of Geography, The Ohio State University, OH, United States

Project: <i>Estimating exposure and health impacts of traffic-related air pollution during daily travel</i>
<br>Supervisor/PI: Huyen TK Le and Joseph Bayer
<br>Funded by: Sustainability Institute seed grant award

<b>GIS Research Assistant.</b>	(May 2018 – July 2018)
<br>The DIGIT Lab, University of Utah, UT, United States

Project: <i>Producing military standard map series for military training around the world</i>
<br>Supervisor: Phoebe B. Mcneally
<br>Funded by: Rockwell Collins, Inc.


{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}

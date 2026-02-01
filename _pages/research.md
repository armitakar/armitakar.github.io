---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
<b>Interrelationship between pedestrian streetscape, walking perceptions, and willingness: An analysis using Large Language Models and Explainable Artificial Intelligence (AI)</b>
<p align="justify">Walking willingness varies across space and society, due to differences in streetscape characteristics and perceived walking experiences. Existing studies mainly underscore the association between neighborhood environment and walking perceptions. However, due to data limitations, little is known about how micro-level pedestrian streetscape influences spatio-social variations in walking perceptions and willingness. To overcome this gap, this study first leverages multimodal large language models (LLMs) to extract micro-level pedestrian streetscape features, namely sidewalk presence, crosswalk signs and curb ramps, and surface, buffer, and traffic signal types. Next, we examine both causal and predictive relationships between road and pedestrian streetscape features, walking perceptions, and willingness using structural equation modelling (SEM) and explainable machine learning (GPBoost and SHAP). We use a mobility survey dataset of 451 participants, rating 1,197 streets in Columbus, OH, based on three main parameters: perceived visual quality, perceived safety, and walking willingness. Using Street View Images, the LLM model identifies pedestrian features for all survey streets, with over 90% accuracy. The SEM further reveals that pedestrian streetscapes, such as sidewalks, buffers, and curb ramps, positively influence walking willingness, with perceived safety exerting a stronger mediating effect than perceived visual quality. The SHAP analysis aligns with SEM mediation patterns, showing that the contributions of perceived safety and visual quality toward willingness predictions are respectively 29% and 7%. These findings highlight intervention priorities: investments in sidewalks, greenery, and accessible curb ramps in underserved communities to enhance both walking experiences and willingness to walk.</p>
<p align="center"> <img src="/images/TRB_Poster_2026.jpg" style = "border:0"> </p>
<p font size = "8" align="center"><i>The paper was presented at Transportation Research Board Annual Meeting 2026</i></p>



<b>Healthcare Deserts in Virginia:Rural-Urban and Socioeconomic Disparities in Access to Care</b>
<p align="justify">Many rural communities in the United States live in healthcare deserts, areas without timely access to care, leading to higher rates of mortality and chronic disease compared to urban populations. While several studies examine healthcare access aggregately, few examine the unequal distribution of healthcare deserts across rural-urban areas and socio-economic drivers, especially in Virginia (VA). We perform our analysis at county and census tract levels, using drive-time thresholds and provider types to understand varying health desert measures across spatio-temporal scales and healthcare needs. Healthcare facilities are classified into five categories: (1) physicians, (2) outpatient care and community health centers, (3) general and surgical hospitals, (4) specialty hospitals, and (5) mental health facilities. Socio-economic variables include poverty rates, race, vehicle ownership, and health insurance coverage, and rural-urban classification. For each provider type, we calculate an access index representing facilities reachable within 15- and 30-minute driving thresholds. Areas with an index of zero are considered healthcare deserts. We use binary logistic regression to examine socio-economic and rural-urban factors influencing likelihood of an area being a healthcare desert. Our results reveal that using an appropriate spatial scale is crucial to better understand healthcare desert; deserts become more identifiable at finer spatial scales. Rural areas with additional socio-economic disadvantages (e.g., no medical insurance) are more likely to be classified as health deserts. Findings can help practitioners and policymakers target healthcare-disadvantaged communities to develop policies, ensuring equitable healthcare access throughout Virginia.</p>
<p align="center"> <img src="/images/GMU_Healthcare_Deserts_TRB presentation.jpg" style = "border:0"> </p>
<p font size = "8" align="center"><i>Healthcare desert maps using 15-minute driving thresholds and at the county (left) and tract-level (right). Deserts consistently appear in eastern and southwestern VA, regardless of spatial scale. The tract-level analysis reveals a stronger health desert pattern than the county-level analysis. More deserts appear in central and northern VA at the tract level.</i></p>



<b>Exploring Determinants of Prenatal Care Travel</b>
<p align="justify">Proximity enables interaction, but what else influences where people go? Using 19.8 million prenatal trips to maternal healthcare facilities across Florida (2016-2022), constructed from patient hospital electronic visitation records, we examine how spatial, socioeconomic, and facility characteristics influence travel. We estimate a negative binomial model of trip counts incorporating origin-, destination- and flow-based predictors. While distance remains a dominant deterrent, its influence is conditioned by rurality, facility capacity, and community health context. These patterns underscore that prenatal maternal travel reflects broader contextual factors beyond geographic distance.</p>
<p align="center"> <img src="/images/Florida_OD_flow_map.jpg" style = "border:0"> </p>
<p font size = "8" align="center"><i> Origin-destination flow map showing prenatal visits in Florida.</i></p>


<b>Inclusive Accessibility: A Socially-Sensitive Approach of Incorporating Perceptions into Space-time Accessibility Measures</b>
<p align="justify">My doctoral dissertation focuses on pioneering a novel concept and measure known as inclusive accessibility. This approach integrates people’s diverse travel choices and experiences into advancing space-time accessibility models. I posit this measure as a more realistic and socially aware representation of accessibility, as it distinguishes between the geographic spaces that are physically and perceptually accessible to individuals and social groups. My PhD dissertation also demonstrates application of inclusive accessibility approach in tailoring transportation infrastructure interventions specific to marginalized communities. </p>
<p align="center"> <img src="/images/walking impedance.png" style = "border:0"> </p>
<p align="center"> <img src="/images/Inclusive access.png" style = "border:0"> </p>
<p font size = "8" align="center"><i> The figure illustrates geographic variations in walking perceptions between high-income white men and low-income women of color, along with its influence on the inclusive access measure for these respective social groups. </i></p>



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

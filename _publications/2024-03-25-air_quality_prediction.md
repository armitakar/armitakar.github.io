---
title: "High spatio-temporal resolution predictions of PM2.5 using low-cost sensor data"
collection: publications
permalink: /publication/2024-03-25-air_quality_prediction
excerpt: ''
date: 2024-03-25
venue: 'Atmospheric Environment'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S1352231024001614'
citation: 'Kar, A., Ahmed, M., May, A. A., & Le, H. T. (2024). &quot;High spatio-temporal resolution predictions of PM2. 5 using low-cost sensor data.&quot; <i>Atmospheric Environment, 326, </i> 120486.'
---
We generated PM2.5 predictions at a high spatio-temporal resolution in the Columbus, OH, Denver, CO, and Pittsburgh, PA metropolitan areas using low-cost PurpleAir sensor data. We used multiple modeling approaches, namely random forest (RF), random forest spatial interpolation (RFSI), space-time regression kriging (STRK), and random forest kriging (RFK). We trained separate models for each combination of hour, month, and city to predict PM2.5 concentrations at 8 a.m. and 6 p.m. on any specific day at a spatial resolution of 100m. In most cases, models that account for the spatio-temporal relationships (e.g., STRK, RFK, RFSI) show better performance than non-spatio-temporal machine learning models (e.g., RF). On average, considering all models of all cities, RFSI (mean MAE =1.75, R2 =0.67) and STRK (mean MAE =1.74, R2 =0.63) models perform better than RFK models (mean MAE =2.11, R2 =0.59), and STRK has clearest spatial patterns. We found that kriging models, especially STRK, are superior in capturing the spatio-temporal relationships and resemble the generic land use pattern of the city, while RFSI models are effective when dealing with very large datasets with missing cases. Our study demonstrates a multi-model approach that could inform low-cost sensor deployment to facilitate air quality modeling. Our high-resolution predictions could also facilitate studies on short-term, traffic-based exposure assessment.  

[Download paper here](/files/pm2_5_prediction_model.pdf)

---
title: "Research"
permalink: /research/
author_profile: true
---

## Master's Thesis

### Crop Type Mapping Using Sentinel-1 and Sentinel-2 in the Smallholder Cropping System of the Cotton Belt in Mali

My master's thesis focused on crop type mapping in the heterogeneous smallholder agricultural landscape of Dioila, Mali. The study investigated the potential of multi-temporal Sentinel-1 Synthetic Aperture Radar (SAR) and Sentinel-2 optical observations for distinguishing major crop types across different stages of the growing season.

The research evaluated Sentinel-1 and Sentinel-2 individually and in combination to understand how sensor type and temporal information influence crop classification performance. Machine-learning-based classification was used together with spectral, vegetation, radar, and temporal features.

## Research Objectives

1. Assess the effectiveness of Sentinel-1 and Sentinel-2 observations for crop type classification in heterogeneous smallholder agricultural landscapes.
2. Investigate how classification performance changes across different stages of the growing season.
3. Evaluate whether combining SAR and optical observations improves crop discrimination.
4. Identify important spectral, radar, temporal, and vegetation-related features for distinguishing crop types.

## Study Area

The study was conducted in Dioila, located within the cotton-growing region of Mali, West Africa. The region is characterized by heterogeneous smallholder agricultural systems with relatively small and diverse agricultural parcels.
### Study Area Map

<p align="center">
  <img src="{{ '/images/study_Area_Map.jpg' | relative_url }}" alt="Study area of the research in Dioila, Mali" width="85%">
</p>

<p align="center"><em>Study area and reference data distribution in Dioila, Mali.</em></p>


## Research Workflow

The research workflow included reference-data preparation, Sentinel-1 and Sentinel-2 preprocessing, feature extraction, temporal dataset construction, machine-learning classification, accuracy assessment, and analysis of feature importance.
<p align="center">
  <img src="{{ '/images/workflow.jpg' | relative_url }}" alt="Research workflow for crop type mapping" width="90%">
</p>

<p align="center"><em>Overall research workflow for multi-temporal and multi-sensor crop type classification.</em></p>



## Satellite Data and Methods

### Sentinel-1

Multi-temporal Sentinel-1 SAR observations were used to capture structural and moisture-related information throughout the cropping season. VV and VH backscatter information and derived radar features were incorporated into the classification experiments.

### Sentinel-2

Multi-temporal Sentinel-2 optical imagery provided spectral and vegetation information. Spectral bands and vegetation indices, including NDVI, NDRE, NDMI, and EVI, were used to characterize crop development.

### Multi-Sensor Fusion

Sentinel-1 and Sentinel-2 observations were combined to investigate whether complementary radar and optical information could improve crop classification, particularly when information from an individual sensor was limited.

### Machine Learning

Machine-learning classification was applied to distinguish crop and non-crop land-cover classes using the multi-temporal satellite features. Classification performance was evaluated using independent reference data and standard accuracy metrics.

## Key Findings

Classification performance generally improved as additional observations from the growing season became available.

Sentinel-2 optical observations provided stronger crop discrimination than Sentinel-1 SAR observations when used independently, while combining optical and radar information produced the strongest overall classification performance.

The results also demonstrated the importance of temporal information, showing that observations acquired during later stages of crop development can provide valuable information for distinguishing crop types in heterogeneous smallholder farming systems.

Cross-temporal sensor fusion further demonstrated that earlier optical observations can provide complementary information when concurrent Sentinel-2 imagery is unavailable.
### Crop Classification Map

<p align="center">
  <img src="{{ '/images/Crop_Classification_Map.jpg' | relative_url }}" alt="Crop classification map" width="90%">
</p>

<p align="center"><em>Crop type classification map derived from satellite observations and machine-learning classification.</em></p>

### Feature Importance

The feature-importance analysis was used to examine the contribution of different satellite-derived predictors to crop classification.

<p align="center">
  <img src="{{ '/images/Feature_Importance_Graph_1.png' | relative_url }}" alt="Feature importance analysis" width="85%">
</p>

<p align="center"><em>Feature importance analysis for the crop classification experiments.</em></p>

<p align="center">
  <img src="{{ '/images/Feature_Importance_Graph_2.png' | relative_url }}" alt="Feature importance analysis" width="85%">
</p>

<p align="center"><em>Importance of satellite-derived features across the classification experiments.</em></p>
## Research Internship

### VITO – Flemish Institute for Technological Research, Belgium

During my research internship in the Remote Sensing Department at VITO, I worked on the evaluation and validation of High Resolution Layer Vegetated Land Cover Characteristics (HRL-VLCC) products.

My work focused particularly on agricultural land-cover information and cropping-pattern products across European regions. I worked with geospatial datasets and satellite observations using Python and QGIS and investigated spatial and temporal inconsistencies in agricultural products.

## Previous Research

Before beginning my Erasmus Mundus master's programme, my research focused on climate variability, agricultural production, drought, floods, and environmental hazards in Bangladesh.

My previous work included investigating relationships between climatic variables and crop production, spatial and temporal patterns of drought and temperature extremes, flood susceptibility, and environmental risk.

These experiences provided the foundation for my current interest in integrating Earth Observation, geospatial analysis, environmental modelling, and machine learning for agricultural and environmental applications.

## Future Research Interests

My future research interests include:

- Agricultural Earth Observation
- Crop Type Mapping and Crop Yield Estimation
- Multi-Sensor Remote Sensing
- Satellite Time-Series Analysis
- GeoAI and Deep Learning
- Environmental Modelling
- Climate and Environmental Monitoring
- Food Security
- Climate-Resilient Agriculture

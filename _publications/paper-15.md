---
title: "An improved geographic pattern based residual neural network model for estimating PM2.5 concentrations"
collection: publications
category: manuscripts
permalink: /publication/paper-15
excerpt: 'Author: Heng Su, Yumin Chen*, **Huangyuan Tan***, John P. Wilson, Lanhua Bao, Ruoxuan Chen, Jiaxin Luo'
date: 2024-11-01
venue: 'International Journal of Applied Earth Observation and Geoinformation'
paperurl: 'https://doi.org/10.1016/j.jag.2024.104174'
---
Abstract: Accurate and continuous PM2.5 data is essential for effective prevention of PM2.5 pollution. Despite the achievements of deep learning methods in estimating PM2.5 concentrations, existing neural network models have relied too much on the self-learning capability and have ignored geographic patterns of PM2.5. Few have taken a geographic perspective when modeling PM2.5, resulting in lower model interpretability. In this paper, rather than inputting spatiotemporal information directly into the networks, we propose an improved geographic pattern based residual neural network (IGeop-ResNet) for estimating PM2.5 concentrations in the Beijing-Tianjin-Hebei region (BTH) of China considering spatial heterogeneity and spatial autocorrelation by introducing spatial eigenvector and attention mechanism, as well as the encoding and embedding methods for temporal categorical variables. A DEM-weighted loss function was introduced to enhance the spatial predictive ability, particularly in high-altitude regions. The results show that the IGeop-ResNet model achieves excellent spatial predictive abilities (R2 of 0.925 in terms of station-based cross-validation) and offers a certain level of interpretability compared to the Ori-STResNet (ordinary directly inputs temporal and spatial information in the ResNet model) and the Geop-ResNet model (without the DEM-weighted loss function). Continuous maps derived from the IGeop-ResNet model suggest the PM2.5 concentrations in the BTH region exhibited a downward trend from 2015 to 2018 and experienced a sharp drop in 2017. The results indicate that NO2 is the Granger cause of PM2.5, while the relationship between SO2 and PM2.5 is insignificant.

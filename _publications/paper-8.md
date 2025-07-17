---
title: "A Grid Feature-Point Selection Method for Large-Scale Street View Image Retrieval Based on Deep Local Features"
collection: publications
category: manuscripts
permalink: /publication/paper-8
excerpt: 'Author: Tianyou Chu, Yumin Chen*, Liheng Huang, Zhiqiang Xu, **Huangyuan Tan**'
date: 2020-12-04
venue: 'Remote Sensing'
paperurl: 'https://doi.org/10.3390/rs12233978'
---
Author: Tianyou Chu, Yumin Chen*, Liheng Huang, Zhiqiang Xu, **Huangyuan Tan**

Abstract: Street view image retrieval aims to estimate the image locations by querying the nearest neighbor images with the same scene from a large-scale reference dataset. Query images usually have no location information and are represented by features to search for similar results. The deep local features (DELF) method shows great performance in the landmark retrieval task, but the method extracts many features so that the feature file is too large to load into memory when training the features index. The memory size is limited, and removing the part of features simply causes a great retrieval precision loss. Therefore, this paper proposes a grid feature-point selection method (GFS) to reduce the number of feature points in each image and minimize the precision loss. Convolutional Neural Networks (CNNs) are constructed to extract dense features, and an attention module is embedded into the network to score features. GFS divides the image into a grid and selects features with local region high scores. Product quantization and an inverted index are used to index the image features to improve retrieval efficiency. The retrieval performance of the method is tested on a largescale Hong Kong street view dataset, and the results show that the GFS reduces feature points by 32.27%–77.09% compared with the raw feature. In addition, GFS has a 5.27%–23.59% higher precision than other methods.

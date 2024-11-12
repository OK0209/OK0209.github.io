---
layout: page
title: Lifestyle Profiles by Mobility Data
description: (2022-2023) Can our movement trajectories reveal our lifestyle patterns?
img: assets/img/05 Mobility/01.jpg
importance: 5
category: Academic projects
---
### **Introduction**
In the era of big data, understanding human behavior through the lens of mobility has become increasingly important. Our research at Peking University delves into the intricate patterns of human movement to uncover lifestyle profiles. By analyzing over 500,000 users' trajectory data in Shenzhen, we've developed a framework that mines high-order mobility features, offering insights into daily routines and preferences.

<div class="row justify-content-sm-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.html path="assets/img/05 Mobility/02.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   A representation of the proposed progressive user profiling framework
</div>

### **Research Methodology**
Our approach is methodical and innovative, focusing on the extraction of high-order features from spatial, temporal, and semantic dimensions of human mobility. We've employed a progressive feature extraction strategy that captures the essence of lifestyle through:

- Spatial Features: Analyzing travel motifs and the radius of gyration to understand the extent of users' activities.
- Temporal Features: Utilizing Discrete Fourier Transform (DFT) to decompose mobility time series and reveal daily rhythms.
- Semantic Features: Vectorizing place semantics using word2vec to capture the context of activities.
<div class="row justify-content-sm-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.html path="assets/img/05 Mobility/03.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   The distribution of users’ motifs and average mobility rhythm
</div>

### **Key Findings**
Our study yielded significant insights, identifying seven distinct user clusters with unique lifestyle profiles. These clusters were interpretable and aligned with common sense, showcasing the effectiveness of our approach.

<div class="row justify-content-sm-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.html path="assets/img/04Traffic/05.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   Hierarchical interpretation of the multi-view k-means clustering results
</div>

### **Research Progress** 

The study has been compiled into a preprint titled [**"A framework for mining lifestyle profiles through multi-dimensional and high-order mobility feature clustering"**](https://arxiv.org/abs/2312.00411).


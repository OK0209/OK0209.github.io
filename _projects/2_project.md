---
layout: page
title: Simulation-Based Policy Evaluation
description: (2023-2024) How to evaluate the cost-efficiency of ecological policies in CHANS?
img: assets/img/02SEEMS/02.jpg
importance: 2
category: Academic projects
---
### **Introduction**
Balancing human development with conservation efforts is a global challenge. This project introduces a study conducted in the Wolong National Nature Reserve in Sichuan, China, which employs simulations of **Coupled Human and Natural Systems (CHANS)** to assess the effectiveness of two ecological conservation programs: **Grain-to-Green (G2G) and Firewood-to-Electricity (F2E)**, in protecting the habitat of the giant panda through cost-effectiveness analysis.

By leveraging the **Socio-Econ-Ecosystem Multipurpose Simulator (SEEMS)**, an agent-based model designed for CHANS, this research offers a framework for policymakers to design economically viable and environmentally sustainable policies. It identifies optimal policy combinations that strike a balance between ecological conservation and economic growth, demonstrating the potential to achieve these dual goals within the constraints of limited budgets and the complexities of CHANS.

<div class="row justify-content-sm-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.html path="assets/img/02SEEMS/01.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The map of Wolong National Reserve.
</div>

### **Research Focus**
This study employs the **Socio-Econ-Ecosystem Multipurpose Simulator (SEEMS)**, an agent-based model (ABM) designed to simulate small-scale coupled human and nature systems. The research analyzes the cost-effectiveness of the G2G and F2E programs in terms of financial budget, habitat conservation performance, and local economic impacts.
<div class="row justify-content-sm-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include video.html path="assets/videos/SEEMS.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption">
   SEEMS Model: Simulating Interactions Between Human Activities and Natural Ecosystems
</div>

For G2G programs, the study incorporates a risk factor to simulate the uncertainty of business returns and classifies households into distinct categories based on their risk tolerance and preferences for the income-leisure trade-off, which directly influences their decision to participate in G2G initiatives.

We utilized pathfinding and random walk algorithms to simulate household firewood collection behavior, reflecting real-world practices. This enables a better understanding of how the F2E policy, after influencing household energy use patterns, affects the spatial extent and intensity of firewood collection activities, and consequently, the quality of habitats.
<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/02SEEMS/07.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/02SEEMS/08.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Schematic diagram of the household categorization and firewood follection algorithm
</div>

### **Key Findings**
- **G2G program** achieves optimal financial efficiency at around **500 CNY/Mu**, with diminishing returns beyond **1000 CNY/Mu**. 
- **F2E program** shows a significant increase in electricity consumption and policy costs is observed when the subsidized electricity price drops below **0.3 CNY/kWh**. 
- Comprehensive cost-efficiency analysis shows no significant correlation between financial burden and carbon emissions, but a positive association with habitat quality and a nonlinear relationship with total economic income. 
- Pareto analysis identifies **18 optimal policy combinations** that balance carbon footprint, habitat quality, and financial benefits.

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/02SEEMS/03.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/02SEEMS/04.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/02SEEMS/05.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/02SEEMS/06.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Cost-efficiency analysis and Pareto Analysis of G2G and F2E programs
</div>

### **Research Progress** 
The study has been compiled into a paper **"Reconciling Human Development and Giant Panda Protection Goals: Cost‑Effectiveness of Farmland Reversion and Energy Substitution Programs in Wolong National Reserve."** and submitted to Ecological Modelling.













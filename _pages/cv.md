---
layout: archive
title: "Project/Research"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

1.Urban Micro-traffic Simulation System
======

* This research is based on a self-developed urban micro-traffic simulation system to investigate and explain complex traffic phenomena. The ultimate goal is to optimize traffic system performance by reducing vehicle travel time and stop frequency, while exploring the necessity and effectiveness of reinforcement learning within simulation-based traffic modeling.

* My work focused on modeling and analyzing the interactions between car-following and lane-changing behaviors, as well as vehicle–signal interactions. In addition, I studied the requirements of simulation environments for reinforcement learning–based traffic signal control.

* The traffic signal control system surrounding Nanjing University of Science and Technology was upgraded and successfully deployed, resulting in a 22.8% reduction in outbound travel time and an 18.5% reduction in inbound travel time, significantly alleviating local traffic congestion. Furthermore, the platform has been applied to optimize traffic operations on more than ten other major arterial roads in Nanjing.

* If you are interested in the actual optimization results : [双向绿波优化南理工周边道路通行](https://www.jsxtgc.org/x3.php?id=37)
  
  <!-- 在Markdown或HTML中添加 -->

<!-- 在 HTML 文件中（如 map.html 或 markdown.md） -->

<video width="640" height="360" controls>
 <source src="/files/lines.mp4" type="video/mp4">
</video>

<p></p>
<p></p>  <!-- 空行 -->
<p></p>

2.State Design in Reinforcement Learning-Based Traffic Signal Control Using Similarity Metrics
======

This study proposes a feature fusion model based on bilinear pooling to enhance the extraction of expressive spatiotemporal features for traffic modeling. By computing the outer product of two feature vectors, bilinear pooling captures high-order interactions between different traffic parameters. Global pooling is then applied to obtain a fixed-dimensional representation. This approach effectively preserves mutual information across multiple traffic features, enabling the model to learn richer spatiotemporal dependencies and achieve stronger representation and prediction capabilities.

<div class="pdf-actions" style="text-align: center; margin: 2em 0;">
 <h3>Full Paper</h3>
 <a href="/files/StateDesign.pdf" class="btn" target="_blank" rel="noopener noreferrer">
 </a>
</div>

<p></p>
<p></p>  <!-- 空行 -->
<p></p>

3.StaPerNet: Feature Stabilization and Period-Level Modeling for Long-Horizon Traffic Forecasting
======

To address the severe non-stationarity in traffic flow data, this study proposes a channel-based feature separation framework that explicitly disentangles stationary and non-stationary components. Noise injection is applied to unstable features during training to enhance robustness, enabling the model to learn a steady-state representation of traffic dynamics. Furthermore, the extracted features are aligned according to their inherent periodic patterns and leveraged for spatiotemporal prediction. Extensive experiments on five public benchmark datasets demonstrate that the proposed method achieves state-of-the-art performance.

<div class="pdf-actions" style="text-align: center; margin: 2em 0;">
 <h3>Full Paper</h3>
 <a href="/files/StaPer.pdf" class="btn" target="_blank" rel="noopener noreferrer">
 </a>
</div>

<p></p>
<p></p>  <!-- 空行 -->
<p></p>

4.State Encoding for Efficient Traffic Signal Control in High Volume
======

A biased state encoding model based on prior knowledge is proposed to improve exploration efficiency under limited computational resources and to mitigate potential out-of-distribution (OOD) errors after real-world deployment. By leveraging domain knowledge, the model identifies regions of the state space that are more informative and allocates greater representational emphasis to these regions through biased state encoding, thereby expanding the effective exploration space while reducing computational cost. Furthermore, the encoding mechanism enables unvisited states to be mapped to semantically similar trained states, enhancing the model’s extrapolation capability and robustness to unseen scenarios.

<div class="pdf-actions" style="text-align: center; margin: 2em 0;">
 <h3>Full Paper</h3>
 <a href="/files/Encoder.pdf" class="btn" target="_blank" rel="noopener noreferrer">
 </a>
</div>

<p></p>
<p></p>  <!-- 空行 -->
<p></p>

5.My Master's Thesis
======

<div class="pdf-actions" style="text-align: center; margin: 2em 0;">
 <h3>Full Paper</h3>
 <a href="/files/master.pdf" class="btn" target="_blank" rel="noopener noreferrer">
 </a>
</div>
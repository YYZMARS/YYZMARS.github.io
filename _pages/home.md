---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /home/
  - /home.html
---

I am currently pursuing the Ph.D degree advised by [Prof. Yue Wu](https://ywuchina.github.io/) with the School of Computer Science and Technology, [MoE Key Lab of Collaborative Intelligence Systems](https://cois.xidian.edu.cn/), Xidian University. I was recommended for admission to the School of Computer Science and Technology at Xidian University to pursue a master's degree in 2020. In 2022, I continued my studies as a successive postgraduate and doctoral program student. 

<h1>🎉 News</h1>
<div class="news" style="overflow-y:auto; height:150px; width:50%; box-sizing: border-box;">
    <ul style="margin: 0; padding: 0; list-style: none;">
        <li style="line-height: 1.5; padding: 5px 0; margin: 0;">[01, 2025]&nbsp;&nbsp; 入选中国科协青年人才托举工程博士生专项计划.</li>
        <li style="line-height: 1.5; padding: 5px 0; margin: 0;">[12, 2024]&nbsp;&nbsp; 2 papers accepted to <h7 style="color: #4169E1;">AAAI 2025</h7>.</li>
        <li style="line-height: 1.5; padding: 5px 0; margin: 0;">[10, 2024]&nbsp;&nbsp; 1 papers accepted to <h7 style="color: #4169E1;">IEEE TNNLS</h7>.</li>
        <li style="line-height: 1.5; padding: 5px 0; margin: 0;">[05, 2024]&nbsp;&nbsp; 1 papers accepted to <h7 style="color: #4169E1;">ICML 2024</h7>.</li>
        <li style="line-height: 1.5; padding: 5px 0; margin: 0;">[02, 2024]&nbsp;&nbsp; 1 papers accepted to <h7 style="color: #4169E1;">CVPR 2024</h7>.</li>
        <li style="line-height: 1.5; padding: 5px 0; margin: 0;">[12, 2023]&nbsp;&nbsp; 1 papers accepted to <h7 style="color: #4169E1;">IEEE TVCG</h7>.</li>
    </ul>
</div>

<h1>🔬 Research Interests</h1>
- Unsupervised/Self-supervised Learning.
- Efficient 3D Computer Vision.
- Low Overlapping 3D Rigid Point Cloud Registration.
- Multimodal Learning for 3D Computer Vision.
- Diffusion Model.


<h1>🏆 Awards</h1>
- National Scholarship, 2024.
- Excellent MindSpore Developers, 2023.
- The First Prize, CAAI The 7th Chinese Youth Congress on Artifical Intelligence, 2022.
- National Scholarship, 2021.


<h1>📖 Selected Publications</h1>
<h2 style="margin: 0 0 0 0">Journal</h2>
{% for post in site.publications_j reversed %} {% include archive-single-pub2.html %} {% endfor %}
<h2 style="margin: 0 0 0 0">Conference</h2>
{% for post in site.publications_c reversed %} {% include archive-single-pub2.html %} {% endfor %}




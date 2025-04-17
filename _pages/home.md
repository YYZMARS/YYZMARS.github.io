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

<div style="background: linear-gradient(135deg, #fdf6e3, #fefcea); border: 2px dashed #e5c07b; border-radius: 12px; padding: 20px; margin-bottom: 30px; box-shadow: 2px 2px 5px rgba(0,0,0,0.1); font-family: 'Courier New', Courier, monospace;">
  <h2 style="margin-top: 0; font-size: 1.5em; color: #d2691e;">🧾 Blackboard Bulletin</h2>
  <ul style="list-style: square; padding-left: 1.2em; color: #333;">
    <li><strong>2025-04-17</strong> — 📝 Our paper on inlier confidence calibration has been accepted by <em>CVPR 2025</em>! <a href="/files/paper.pdf" style="text-decoration: underline;">[PDF]</a></li>
    <li><strong>2025-03-28</strong> — 🧠 Delivered a guest lecture on diffusion models at COIS Lab.</li>
    <li><strong>2025-02-20</strong> — 🎓 Recommended as a candidate for the China Association for Science and Technology Youth Talent Program.</li>
  </ul>
</div>



<h1>🔬 Research Interests</h1>
- Unsupervised/Self-supervised Learning.
- Efficient 3D Computer Vision.
- Low Overlapping 3D Rigid Point Cloud Registration.
- Multimodal Learning for 3D Computer Vision.
- Diffusion Model.


<h1>🏆 Honors and Awards</h1>
- 入选首批中国科协青年人才托举工程博士生专项计划, 2025.
- National Scholarship, 2024.
- MindSpore Excellent Developers, 2023.
- The First Prize, CAAI The 7th Chinese Youth Congress on Artifical Intelligence, 2022.
- National Scholarship, 2021.


<h1>📖 Selected Publications</h1>
<h2 style="margin: 0 0 0 0">Journal</h2>
{% for post in site.publications_j reversed %} {% include archive-single-pub2.html %} {% endfor %}
<h2 style="margin: 0 0 0 0">Conference</h2>
{% for post in site.publications_c reversed %} {% include archive-single-pub2.html %} {% endfor %}




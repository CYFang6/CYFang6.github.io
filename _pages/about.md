---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  dl {
    margin-top: 1px;
    margin-bottom: 5px; /* 调整这个值以获得合适的间距 */
    clear: both;
  }

  img {
    display: block;
    margin: 0px 10px 10px 0px; /* 图片居中 上右下左*/ 
    max-width: 100%; /* 限制图片最大宽度 */
  }

  hr {
    border: 1px solid #ebebeb; /* 调整分隔线的颜色和样式 */
    /* margin: 10px;  */
    clear: both; 
  }


  dl dd {
  color: #; 
  margin-top: 1px; 
  margin-bottom: 1px;
}

  dl dd strong {
  font-weight: bold;
  }


  .publication-title {
    font-weight: bold;
  }

  .submission-title {
    font-weight: bold;
  }

  .image-container {
    display: flex;
    justify-content: center;
    gap: 10px; /* 控制图片间距 */
    margin: 20px 0;
  }

  .image-container img {
    max-width: 150px; /* 控制最大宽度 */
    height: auto;
    margin: 0; /* 移除原来的 margin */
  }

  .co-first {
    color: #B02418;
  }

  .spotlight {
    color: #B02418;
  }
  
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


# Short Bio

Hi there! This is Chengying Fang (方程瑛), I am a first-year graduate student at [School of Computer Science at Wuhan University](https://cs.whu.edu.cn/), advised by Prof. [Mang Ye](https://scholar.google.com/citations?user=j-HxRy0AAAAJ&hl=zh-CN). If you are interested in collaborating with me or want to have a chat, always feel free to contact me through e-mail！

My research mainly focuses on **Federated Learning** and **Large Language Model**.




# 🔥 News
<div style="max-height: 200px; overflow-y: auto;">
<ul>
  <li><em>2025.05:</em> 🌟 FedPHA was accepted to <strong>ICML 2025</strong>.</li>
</ul>
</div>

# 📝 Publications 

&dagger;: equal contribution, * : corresponding author

<hr>

<dl>
  <dt><img align="left" width="400" src="../images/paper/FedPHA.jpg" alt="FedPHA"></dt>
  <dd><a class="publication-title">FedPHA: Federated Prompt Learning for Heterogeneous Client Adaptation</a></dd>
  <dd><strong>Chengying Fang<sup>&dagger;</sup></strong>, Wenke Huang<sup>&dagger;</sup>, Guancheng Wan<sup>&dagger;</sup>, Yihao Yang, Mang Ye*</dd>
  <dd>International Conference on Machine Learning  <strong>(ICML)</strong>, 2025</dd>
  <dd>
    <a href="https://openreview.net/forum?id=y7pDvbi9xz" target="_blank">📄 Paper</a> |
    <a href="https://github.com/CYFang6/FedPHA" target="_blank">💻 Code</a>
  </dd>
</dl>

<hr>
<hr>

# 📖 Educations

- *2024.09 - now*, Master Student, School of National Cybersecurity, Wuhan University, China.
- *2020.09 - 2024.06*, Bachelor, School of National Cybersecurity, Wuhan University, China.

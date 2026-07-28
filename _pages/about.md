---
permalink: /
title: "Rui Austin Liu"
excerpt: "Assistant Professor at Xiamen University studying intellectual property, innovation, and patent policy."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p class="academic-eyebrow">Assistant Professor · Xiamen University</p>

<p class="academic-lead">I study how intellectual property institutions shape firm behavior, technology markets, and the value of innovation.</p>

I am an Assistant Professor at the [Intellectual Property Research Institute, Xiamen University](http://www.iprixmu.com/page264.html?article_id=2037). I received my PhD in Management from the Shanghai International College of Intellectual Property at Tongji University in 2025 and was a jointly trained doctoral researcher at the [Max Planck Institute for Innovation and Competition](https://www.ip.mpg.de/en/) from October 2024 to March 2025. I also hold a Juris Master from Xiamen University and a Bachelor of Engineering from Southwest University of Political Science and Law.

My current work combines intellectual property management, innovation economics, and patent policy. A central strand of my research examines patent disclosure: when earlier disclosure improves technology transactions and knowledge diffusion, and when it instead encourages strategic filing or erodes innovation value. I am also interested in the intersection of intellectual property and national security, and in intellectual property issues emerging in the age of AI.

<div class="academic-actions">
  <a class="academic-button academic-button--primary" href="/publications/">View publications</a>
  <a class="academic-button" href="https://scholar.google.com/citations?user=OB_k4UQAAAAJ&hl=zh-CN">Google Scholar</a>
</div>

## Research interests

<div class="research-grid">
  <div class="research-card">
    <span class="research-card__number">01</span>
    <h3>Patent disclosure</h3>
    <p>Strategic disclosure, patent quality, knowledge spillovers, and innovation value.</p>
  </div>
  <div class="research-card">
    <span class="research-card__number">02</span>
    <h3>Technology markets</h3>
    <p>Information asymmetry, technology transactions, and the commercialization of patents.</p>
  </div>
  <div class="research-card">
    <span class="research-card__number">03</span>
    <h3>IP &amp; emerging challenges</h3>
    <p>National security, artificial intelligence, and new questions for intellectual property governance.</p>
  </div>
</div>

## Teaching

<div class="teaching-grid">
  <article class="teaching-card">
    <p class="teaching-card__level">Graduate / 研究生</p>
    <ul class="course-list">
      <li>
        <span class="course-title">Topics in Patent Law</span>
        <span class="course-title-zh">专利法专题</span>
      </li>
      <li>
        <span class="course-title">Intellectual Property Search</span>
        <span class="course-title-zh">知识产权检索</span>
      </li>
    </ul>
  </article>
  <article class="teaching-card">
    <p class="teaching-card__level">Undergraduate / 本科生</p>
    <ul class="course-list">
      <li>
        <span class="course-title">The Detective’s Handbook</span>
        <span class="course-title-zh">侦探养成手册</span>
      </li>
    </ul>
  </article>
</div>

## Selected publications

<p class="publication-ranking-legend"><strong>NSFC A</strong><span>国家自然科学基金管理科学部 A 类期刊</span></p>

{% assign selected_publications = site.publications | where: "selected", true | sort: "date" | reverse %}
{% for post in selected_publications %}
  {% include archive-single.html home=true %}
{% endfor %}

<p class="section-link"><a href="/publications/">See all publications <span aria-hidden="true">→</span></a></p>

## Contact

For research correspondence, please email [forensicscience@foxmail.com](mailto:forensicscience@foxmail.com). I publish under the name **Rui Liu (刘睿)**.

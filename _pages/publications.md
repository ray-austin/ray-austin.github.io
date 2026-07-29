---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<p class="academic-eyebrow">Research output</p>
<p class="academic-lead academic-lead--compact">Selected peer-reviewed and online-first work on intellectual property, innovation, technology markets, and research-data governance.</p>

{% include base_path %}

<div class="publication-note">
  <span>Profiles</span>
  <a href="{{ site.author.googlescholar }}">Google Scholar</a>
  <a href="{{ site.author.orcid }}">ORCID</a>
</div>

<h2 class="publication-section-title">Working papers</h2>

{% for paper in site.data.working-papers %}
<div class="list__item">
  <article class="archive__item" itemscope itemtype="http://schema.org/ScholarlyArticle">
    <h3 class="archive__item-title" itemprop="headline">
      <a href="{{ paper.url }}" target="_blank" rel="noopener">{{ paper.title }}</a>
    </h3>
    <p class="publication-authors" itemprop="author">{{ paper.authors }}</p>
    <p class="publication-meta"><i>{{ paper.venue }}</i>, {{ paper.year }} <span class="publication-status">{{ paper.status }}</span></p>
    <div class="archive__item-excerpt" itemprop="description"><p>{{ paper.excerpt }}</p></div>
    <p class="publication-links">
      {% if paper.pdf %}<a href="{{ paper.pdf | relative_url }}" target="_blank" rel="noopener">PDF</a>{% endif %}
      <a href="{{ paper.url }}" target="_blank" rel="noopener">SSRN</a>
      <a href="{{ paper.doi }}" target="_blank" rel="noopener">DOI</a>
    </p>
  </article>
</div>
{% endfor %}

<h2 class="publication-section-title publication-section-title--later">Intellectual property &amp; innovation</h2>

{% assign current_publications = site.publications | where: "section", "current" | sort: "date" | reverse %}
{% for post in current_publications %}
  {% include archive-single.html %}
{% endfor %}

<h2 class="publication-section-title publication-section-title--later">Earlier research</h2>

{% assign earlier_publications = site.publications | where: "section", "earlier" | sort: "date" | reverse %}
{% for post in earlier_publications %}
  {% include archive-single.html %}
{% endfor %}

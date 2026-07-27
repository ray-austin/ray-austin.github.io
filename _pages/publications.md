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

<h2 class="publication-section-title">Intellectual property &amp; innovation</h2>

{% assign current_publications = site.publications | where: "section", "current" | sort: "date" | reverse %}
{% for post in current_publications %}
  {% include archive-single.html %}
{% endfor %}

<h2 class="publication-section-title publication-section-title--later">Earlier research</h2>

{% assign earlier_publications = site.publications | where: "section", "earlier" | sort: "date" | reverse %}
{% for post in earlier_publications %}
  {% include archive-single.html %}
{% endfor %}

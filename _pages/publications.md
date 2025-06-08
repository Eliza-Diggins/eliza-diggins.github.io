---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<style>
  .publications-intro {
    background: #f9f9fb;
    border-left: 5px solid #0066cc;
    padding: 18px 24px;
    border-radius: 10px;
    margin-bottom: 30px;
    box-shadow: 0 2px 6px rgba(0, 0, 0, 0.05);
  }
  .wordwrap a {
    font-weight: bold;
    color: #0066cc;
    text-decoration: none;
  }
</style>

<div class="publications-intro">
  <p style="font-size: 1.15em; margin-bottom: 0.8em;">
    Over the past few years, I’ve worked on projects spanning computational astrophysics,
    biomedical data science, and inclusive pedagogy. Below is a selection of my publications,
    including peer-reviewed journal articles, collaborative research, and conference abstracts.
  </p>
  <p>
  I might be a little bit slow to update this page directly, so for a fully up-to-date list of my publications,
  please check the google scholar profile linked below.
  </p>
  {% if site.author.googlescholar %}
    <p class="wordwrap">
      For a full list, see <a href="{{ site.author.googlescholar }}" target="_blank">my Google Scholar profile →</a>
    </p>
  {% endif %}
</div>

{% include base_path %}

<div class="publications-list">
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
</div>
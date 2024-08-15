---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

{% include_relative includes/intro.md %}

{% include_relative includes/news.md %}

{% include_relative includes/pub.md %}

{% include_relative includes/honors.md %}

{% include_relative includes/education.md %}

{% include_relative includes/internships.md %}

{% include_relative includes/services.md %}


<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=100&t=n&d=CCd_LMjpOvK7hx6Be_HZm5Kn0d2E9qZ8g1hJHBK5ePU'></script>
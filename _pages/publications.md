---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  You can also find my articles on <u><a href="https://scholar.google.com/citations?hl=en&user=Z_l5f-4AAAAJ">my Google Scholar profile</a>.</u>

{% include base_path %}
<h1>2019</h1>



{% for post in site.publications reversed %}
  
  {% if post.year == 2019 %}
  {% include archive-single.html  %}
  
  {% endif %}
{% endfor %}

<h1>2018</h1>



{% for post in site.publications reversed %}
  
  {% if post.year == 2018 %}
  {% include archive-single.html  %}
  
  {% endif %}
{% endfor %}




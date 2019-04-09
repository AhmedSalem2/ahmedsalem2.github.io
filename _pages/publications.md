---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
<h1>2018</h1>



{% for post in site.publications reversed %}
  
  {{ assign dateTemp = post.date | date: %Y" }}
  {{dateTemp}}  
  {{post.date}}
  {{@post.date}}
  {{post.date > 2019}}
  {% if dateTemp > 2018 %}
  {% include archive-single.html  %}
  
  {% endif %}
{% endfor %}




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
<h1>2019</h1>
{{ base_path }}
{{ site.publications }}

{% for post1 in site.publications reversed %}
{{post1}}

{% for post in post1 reversed %}
{{post}}
  {% include archive-single.html %}
{% endfor %}
{% endfor %}


{% for post in site.publications.2019 reversed %}
  {% include archive-single.html %}
{% endfor %}
<h1>2018</h1>

{% for post in site.publications.2018 reversed %}
  {% include archive-single.html %}
{% endfor %}

---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
year: "2023"
---

<h2>2024</h2>
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

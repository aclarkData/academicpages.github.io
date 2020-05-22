---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

<h2>Machine Learning</h2>
{% include base_path %}

<h2>Economics</h2>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

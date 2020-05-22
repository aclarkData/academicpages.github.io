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

<a href="#ML">Machine Learning Publications</a>
<a href="#Econ">Economics Publications</a>

<p id="ML"><h1>Machine Learning</h1></p>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



<p id="Econ"><h1>Economics</h1></p>
{% for post in site.publicationsecon reversed %}
  {% include archive-single.html %}
{% endfor %}

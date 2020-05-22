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

<h1><a href="#ML">Machine Learning Publications</a></h1>
<br>

<h1><a href="#Econ">Economics Publications</a></h1>

<p id="ML"><h1>Machine Learning</h1></p>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


<p id="Econ"><h1>Economics</h1></p>

<h2>Why Private Cryptocurrencies Cannot Serve as International Reserves but Central Bank Digital Currencies Can</h2>
<br>

Working paper about Why Private Cryptocurrencies Cannot Serve as International Reserves but Central Bank Digital Currencies Can.
<br>
[Access the article here](https://aclarkdata.github.io/files/Why%20Private%20Cryptocurrencies%20Cannot%20Serve%20as%20InternationalReserves%20but%20Central%20Bank%20Digital%20Currencies%20Can.pdf)
<br>
Recommended citation: Clark and Mihailov (June 2019). "Why Private Cryptocurrencies Cannot Serve as International Reserves but Central Bank Digital Currencies Can" Economic Analysis Research Group (EARG). Discussion Paper No. 2019-09. University of Reading
http://www.reading.ac.uk/web/files/economics/emdp201909.pdf

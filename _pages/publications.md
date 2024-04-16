---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can find my articles on <a href="{{site.author.googlescholar}}">Google Scholar</a> or <a href="https://dblp.org/pid/126/6037.html">DBLP</a>. </div>
{% endif %}

Below there are several recent publications. 


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">Here is a selection of my publications. You can also find a more exhaustive list of my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a> or on my <a href="/CV/">CV</a> .</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

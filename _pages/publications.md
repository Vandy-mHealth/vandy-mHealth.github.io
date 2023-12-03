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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<hr>
<sup>*</sup>: Equal authorship <br/>
<i class="fas fa-fw fa-user-graduate zoom"  style="color:#866D4B;" aria-hidden="true"></i>: VU undergrad author <br/>
🇺🇸: country affiliations of authors <br/>

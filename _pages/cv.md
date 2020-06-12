---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

{% capture toc %}
{% include toc_pure_liquid.html html=content sanitize=true h_min=1 h_max=1 %}
{% endcapture %}

{% unless toc == blank %}
    <h1>{{ site.TOC }}</h1>
    <div class='whatTheTOC'>{{ post.summary }}</div>
    {{ toc }}
{% endunless %}

Current
======
  {% include cv/current.html %}

Education
======
  {% include cv/educ.html %}

Refereed Publications
======
    {% include cv/rfpub.htm %}

Other Publications
======
    {% include cv/othpub.htm %}

Work in Progress
======
  {% include cv/wkpap.htm %}

PhD Students
======
  {% include cv/stud.html %}

Other Supervision of Students
======
  {% include cv/super.html %}

Experience
======
  {% include cv/exper.html %}

Conference and Seminar Presentations
======
  {% include cv/conf.htm %}

Grants and Research Contracts
======
  {% include cv/grant.htm %}

Current Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Previous Teaching
======
  {% include cv/class.htm %}

Administration and Service
======
  {% include cv/admin.htm %}

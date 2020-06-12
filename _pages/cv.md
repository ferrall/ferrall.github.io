---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Current
======
  {% include cv/current.html %}

Education
======
  {% include cv/educ.html %}

Publications
======
    <ul>{% for post in site.publications %}
      {% include archive-single-cv.html %}
    {% endfor %}</ul>

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

---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

{% include toc %}

# Current
  {% include cv/current.html %}

# Education
  {% include cv/educ.html %}

# Publications

## Refereed Publications
    {% include cv/rfpub.htm %}

## Other Publications
    {% include cv/othpub.htm %}

## Work in Progress
  {% include cv/wkpap.htm %}

# Superivision

## PhD Students
  {% include cv/stud.html %}

## Other Supervision
  {% include cv/super.html %}

# Experience
  {% include cv/exper.html %}

# Conference and Seminar Presentations
  {% include cv/conf.htm %}

# Grants and Research Contracts
  {% include cv/grant.htm %}

# Teaching

## Current
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Previous Teaching
  {% include cv/class.htm %}

# Administration and Service
  {% include cv/admin.htm %}

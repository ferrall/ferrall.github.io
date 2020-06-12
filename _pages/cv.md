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
  <dl>  {% include cv/educ.html %}  </dl>

# Publications

## Refereed Publications
  {% include cv/rfpub.htm %}

## Other Publications
  <dl> {% include cv/othpub.htm %} </dl>

## Work in Progress
  <dl> {% include cv/wkpap.htm %} </dl>

# Supervision

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

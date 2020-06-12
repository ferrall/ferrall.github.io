---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


{% include includes/cv/head.htm}
{% include includes/cv/exper.htm}
{% include includes/cv/stud.htm}
{% include includes/cv/super.htm}

{% for post in site.includes/cv  %}
  {% include archive-single.html %}
{% endfor %}

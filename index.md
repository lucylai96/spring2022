---
layout: home
title: GenEd 1125
nav_exclude: true
seo:
  type: Course
  name: Artificial and Natural Intelligence
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% for module in site.modules %}
{{ module }}
{% endfor %}

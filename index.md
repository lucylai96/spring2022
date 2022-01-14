---
layout: home
title: Home
nav_exclude: false
nav_order: 1
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

Here is a [PDF version](https://canvas.harvard.edu/files/14152907/download?download_frd=1) of the course schedule and syllabus.
Here is the [Zoom Recording](https://canvas.harvard.edu/courses/97916/external_tools/71135) of the course preview, where Prof. Murthy gives an overview of the course.

{% for module in site.modules %}
{{ module }}
{% endfor %}

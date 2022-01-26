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

**Instructor: Professor Venkatesh Murthy**  ([vnmurthy@fas.harvard.edu](mailto:vnmurthy@fas.harvard.edu)) \
**Head TF: Lucy Lai**  ([lucylai@g.harvard.edu](mailto:lucylai@g.harvard.edu)) \
**Lecture: M/W 3-4:15PM | Science Center Hall E**

Quick Links
* [PDF version](https://canvas.harvard.edu/files/14228300/download?download_frd=1) of the course schedule and syllabus.
* [Course Preview Zoom Recording](https://harvard.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=ea20130f-9f05-40ee-835b-ae1d0145500a), where Prof. Murthy gives an overview of the course.

{% for module in site.modules %}
{{ module }}
{% endfor %}

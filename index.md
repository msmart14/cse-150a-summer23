---
layout: home
title: 🏠 Home
nav_exclude: false
nav_order: 1
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

<!-- for the old icon: >
 <!-- <img src='favicon.ico' style='vertical-align: text-top' width=37> -->

{{ site.staffersnobio }}

[Jump to the current week](#week-1-probability-basics){: .btn }
<!-- [Recordings](https://podcast.ucsd.edu/){: .btn .btn-blue } -->



{: .warning }
**This site is under construction and everything is subject to change!**

<!-- {: .note }
To view the lecture recordings, click on the 🎥 button for each lecture. -->


{% for module in site.modules %}
{{ module }}
{% endfor %}

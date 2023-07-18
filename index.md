---
layout: home
title: Home
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

[Jump to the current week](#week-3-em-hmm-and-take-home-midterm){: .btn }
<!-- [Recordings](https://podcast.ucsd.edu/){: .btn .btn-blue } -->



<!-- {: .warning }
**This site is under construction and everything is subject to change!** -->

{: .note }
To view the lecture recordings, click on the 🎥 button for each lecture.


<iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=1&bgcolor=%23ffffff&ctz=America%2FLos_Angeles&mode=WEEK&src=Y18wNGM0Zjk4MGU3NTNhNjA4MWJjOWYxMjAzYjhkMmQ2N2MyOTVjZjk3ZTIwYWQwNzU1ZGQ3ZTZjNjUwOWZmNTUzQGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&color=%23E4C441" style="border:solid 1px #777" width="800" height="600" frameborder="0" scrolling="no"></iframe>

{% for module in site.modules %}
{{ module }}
{% endfor %}

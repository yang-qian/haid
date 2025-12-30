---
layout: page
title: Semester Schedule
description: Listing of course modules and topics.
nav_order: 2
---

# Course Schedule

<!-- Annotations in this table: **homework**{: .label .label-hw-due }
**in-class student presentation**{: .label .label-green }
<a href="https://www.microsoft.com/en-us/research/publication/power-to-the-people-the-role-of-humans-in-interactive-machine-learning/">recommended readings</a>. -->

{% for module in site.modules %}
{{ module }}
{% endfor %}

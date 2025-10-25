---
layout: default
title: "Printable Portfolio"
permalink: /print/
class: print-page
---

# Muntasir Mahdi – Portfolio
_Virginia Tech | Auburn University_

---

# Graduate Projects
{% assign grad_projects = site.projects | where: "category", "Graduate Research" | sort: "importance" %}
{% for project in grad_projects %}
<div style="page-break-after: always;">
  <h2>{{ project.title }}</h2>
  <p><em>{{ project.description }}</em></p>
  {{ project.content }}
</div>
{% endfor %}

# Undergraduate Projects
{% assign undergrad_projects = site.projects | where: "category", "Undergraduate Projects" | sort: "importance" %}
{% for project in undergrad_projects %}
<div style="page-break-after: always;">
  <h2>{{ project.title }}</h2>
  <p><em>{{ project.description }}</em></p>
  {{ project.content }}
</div>
{% endfor %}

---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our team spans undergraduate, masters, and doctoral students.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="group == 'PI'" %}

# Current Members
{% include list.html data="members" component="portrait" filter="group == 'current'" %}

# External Members
{% include list.html data="members" component="portrait" filter="group == 'external'" %}

# Alumni
{% include list.html data="members" component="portrait" filter="group == 'alumni'" %}

{% include grid.html style="square" content=content %}

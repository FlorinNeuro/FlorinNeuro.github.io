---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi, alumni: false" %}
<br>
{% include list.html data="members" component="portrait" filters="role: postdoc, alumni: false" %}
<br>
{% include list.html data="members" component="portrait" filters="role: ^(?!pi|postdoc|shk|alumni$), alumni: false" %}
<br>
{% include list.html data="members" component="portrait" filters="role: shk, alumni: false" %}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-user-graduate" %} Alumni

{% include section.html %}

{% include list.html data="members" component="portrait" style="small" filters="alumni: true" %}

---
title: Our Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team



{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: Research Associate" %}
{% include list.html data="members" component="portrait" filters="role: Research Assistant" %}
{% include list.html data="members" component="portrait" filters="role: PhD" %}
{% include list.html data="members" component="portrait" filters="role: MSc" %}
{% include list.html data="members" component="portrait" filters="role: UG" %}
{% assign excluded_roles = "pi,Research Associate,Research Assistant,PhD,MSc,UG" | split: "," %}
{% assign remaining_members = site.data.members | where_exp: "member", "excluded_roles contains member.role == false" %}
{% include list.html data=remaining_members component="portrait" %}
{% include section.html background="images/background.jpg" dark=true %}


{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}



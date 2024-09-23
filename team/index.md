---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi, alumni: " %}
{% include list.html data="members" component="portrait" filters="role: resident, alumni: " %}
{% include list.html data="members" component="portrait" filters="role: researcher, alumni: " %}
{% include list.html data="members" component="portrait" filters="role: phd, alumni: " %}
{% include list.html data="members" component="portrait" filters="role: med-student, alumni: " %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: resident, alumni: true" %}
{% include list.html data="members" component="portrait" filters="role: researcher, alumni: true" %}
{% include list.html data="members" component="portrait" filters="role: phd, alumni: true" %}
{% include list.html data="members" component="portrait" filters="role: med-student, alumni: true" %}

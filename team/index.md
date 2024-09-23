---
title: Members
nav:
  order: 3
  tooltip: About our lab members
---

# {% include icon.html icon="fa-solid fa-users" %}Members

The EMBER Lab is powered by a diverse and talented group of researchers, students, and clinicians.
Under the leadership of Dr. Kelly Collins, our team brings together expertise from neuroscience, engineering, and neurosurgery.
Our current members are actively engaged in a wide range of projects, while our past members continue to make meaningful contributions to science and medicine.
This page offers an overview of our current lab team, as well as a look at the alumni who have helped shape our lab’s journey.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi, alumni: " %}
{% include list.html data="members" component="portrait" filters="role: resident, alumni: " %}
{% include list.html data="members" component="portrait" filters="role: researcher, alumni: " %}
{% include list.html data="members" component="portrait" filters="role: phd, alumni: " %}
{% include list.html data="members" component="portrait" filters="role: med-student, alumni: " %}

{% include section.html background="images/background.jpg" dark=true %}

## Alumni

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: resident, alumni: true" %}
{% include list.html data="members" component="portrait" filters="role: researcher, alumni: true" %}
{% include list.html data="members" component="portrait" filters="role: phd, alumni: true" %}
{% include list.html data="members" component="portrait" filters="role: med-student, alumni: true" %}

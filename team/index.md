---
title: Team
nav:
  order: 1
  tooltip: About our team
---


# {% include icon.html icon="fa-solid fa-users" %}Meet the team
<div style="text-align: center; font-size: 20px;">

We are a multidisciplinary team of physicists, clinicians, and neuroscientists dedicated to developing and applying advanced imaging methods to study the brain in both healthy and pathological conditions, with a particular emphasis on neurofluids, stroke, dementia, and brain plasticity.

</div>

{% include section.html %}

## Principle Investigators
{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

## Technical Specialists
{% include list.html data="members" component="portrait" filter="role == 'experimental-officer'" %}
{% include list.html data="members" component="portrait" filter="role == 'technician'" %}


## Junior Fellows and Postdoctoral Researchers
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}


## PhD Students
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}

{% include section.html background="images/background.jpg" dark=true %}

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %} -->


---
---

<div style="text-align: center; font-size: 50px;">
<strong>N</strong>euro<strong>I</strong>maging and <strong>MO</strong>delling group
</div>

<div style="text-align: center; font-size: 24px; margin-bottom: 8rem;">
Our research focusses on development and application of neuroimaging and modelling approaches to study brain physiology.
</div>


{% capture text %}

Take a look at our most recent publications.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/publications.png"
  link="research"
  title="Research"
  flip=false
  text=text
%}

{% capture text %}


Ongoing projects across NIMO teams applying diverse quantitative MRI methods in both clinical and preclinical settings.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/projects.jpg"
  link="projects"
  title="Projects"
  flip=false
  style="bare"
  text=text
%}

{% capture text %}

Our team brings together PIs, technical specialists, postdoctoral researchers, and PhD students from a wide range of scientific backgrounds.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/team.jpg"
  link="team"
  title="Team"
  flip=false
  text=text
%}

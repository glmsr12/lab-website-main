---
title: Home
nav:
  order: 0
  tooltip: Home page
---

# Zeynep H. Gümüş Lab

We are a team of computational geneticists, computer scientists,  engineers, and data visualization design experts who aim to understand genetic drivers of cancer risk, progression and immunotherapy response. We develop new routes to analyze, integrate and explore diverse, massive and heterogenous datasets by utilizing tools from genomic epidemiology, computational genomics, data science, data visualization and ultrafast computing.  You can find our software distributed on [GitHub](https://github.com/GumusLab/ "Our GitHub")!

{% include section.html %}

{% capture text %}

<!--research/publications feature-->
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
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}
<!--software feature-->
{%
  include button.html
  link="tools"
  text="Learn more here"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

<!--team feature-->
{% capture text %}
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
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
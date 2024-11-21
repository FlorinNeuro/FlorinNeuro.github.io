---
---

# Welcome to the Florin Lab !

We are a part of the Institute of Clinical Neuroscience and Medical Psychology at the University Hospital in Düsseldorf.

Many neurological diseases lead to pathological changes in brain signals that are already visible during rest. This makes analyzing spontaneous activity a promising avenue to better understand the brain's function and dysfunction. Our research aims at providing a characterization of the neurophysiological basis of the brain's resting state networks (RSNs) by determining how communication between and within RSNs is mediated. This goal is achieved by analyzing electro-/magnetoencephaolographic (E/MEG) data from healthy participants and Parkinson (PD) patients.

Results obtained are translationally used to improve our understanding of the pathophysiology of neurological diseases such as Parkinson's disease.  A particular focus is on tracing out the electrophysiological mechanisms underlying the effectiveness of dopaminergic treatment and deep brain stimulation for Parkinson patients.
<!-- [Florin](https://github.com/greenelab/lab-website-template) is an easy-to-use, flexible website template for [labs](https://www.greenelab.com/).
Spend less time worrying about managing a website and citations, and more time running your lab. -->

<!-- {%
  include button.html
  type="docs"
  link="https://greene-lab.gitbook.io/lab-website-template-docs"
%}
{%
  include button.html
  type="github"
  text="On GitHub"
  link="greenelab/lab-website-template"
%} -->

{% include section.html %}

## Overview

{% capture text %}

{%
  include button.html
  link="news"
  text="Breaking news !"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="news"
  title="Our News"
  flip=true
  text=text
%}

{% capture text %}

{%
  include button.html
  link="research"
  text="Learn more about our research"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/bahners2022.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

{%
  include button.html
  link="publications"
  text="See our latest publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="publications"
  title="Our Publications"
  flip=true
  style="bare"
  text=text
%}

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
  image="images/group_photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}

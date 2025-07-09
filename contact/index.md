---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our research peaked your interest or curiosity? You wish to collaborate, visit or just discuss with us? Feel free to contact us via email. We will respond in the briefest delay.

{%
  include button.html
  type="email"
  text="esther.florin@hhu.de"
  link="esther.florin@hhu.de"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/hVSzFDguN1RA8YfN7"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/group_photo.jpg"
  caption="Whether it is for work..."
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/keggle_framed.jpg"
  caption="...or fun, contact us!"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}


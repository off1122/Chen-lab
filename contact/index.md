---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our laboratory is located at Room 312, Building 2，Haihe Laboratory of Cell Ecosystem，Yuexin Road, Binhai Hi-Tech Industrial Development Area, Tianjin，300480 China

{%
  include button.html
  type="email"
  text="chenchangya@ihcams.ac.cn"
  link="chenchangya@ihcams.ac.cn"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Amap for easy navigation"
  link="https://www.amap.com/place/B0H0D59ZQT"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/contact/contact1.jpg"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/contact/contact2.jpg"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% comment %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}

{% endcomment %}

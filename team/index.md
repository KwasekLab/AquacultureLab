---
title: People
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Current Members

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!(pi|exmember|mascot)$)" %}
{% include list.html data="members" component="portrait" filters="role: mascot" %}

# {% include icon.html icon="fa-solid fa-users" %}Past Members

{% include list.html data="members" component="portrait" filters="role: exmember" %}

{% include section.html background="images/fish-background.jpeg" dark=true %}

We continuously create research opportunities for students and professionals so if any of our research pillars are of interest to you, please feel free to reach out to us. 

{% include section.html %}

{% capture content %}

{% include figure.html image="images/JohnPete.jpg" %}
{% include figure.html image="images/jj.jpg" %}
{% include figure.html image="images/pete-aubrey.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}

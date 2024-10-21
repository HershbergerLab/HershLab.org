---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi, group: " %}
{% include list.html data="members" component="portrait" filters="role: technician, group: " %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: " %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: masters, group: " %}
{% include list.html data="members" component="portrait" filters="role: programmer, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}
{% include list.html data="members" component="portrait" filters="role: mascot-d, group: " %}
{% include list.html data="members" component="portrait" filters="role: mascot-c, group: " %}

{% include section.html dark=true %}

We are always looking for talented, passionate people to join the lab!
If you have a strong interest in quantitative genetics, plant breeding, vegetable quality characteristics, or data science, please get in touch!

{%
  include button.html
  icon="fa-solid fa-handshake-angle"
  text="Join the Team"
  link="join"
  style="button"
%}

{% include section.html %}


## Alumni

{% include list.html data="members" component="portrait" filters="role: technician, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: masters, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: programmer, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: mascot-d, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: mascot-c, group: alum" style="small" %}

{% include section.html %}


{% capture col1 %}

{%
  include figure.html
  image="images/team/planting_2023.JPEG"
  caption = "Planting butter beans (2023)"
%}

{% endcapture %}

{% capture col2 %}

{% 
  include figure.html 
  image="images/team/team_2024.jpg"
  caption = "Post-planting smiles (2024)" 
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html %}


## Funding

{%
  include figure.html
  image="images/team/funding/funders.png"
%}
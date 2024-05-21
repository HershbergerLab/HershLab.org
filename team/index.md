---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: technician" %}
{% include list.html data="members" component="portrait" filters="role: postdoc" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: masters" %}
{% include list.html data="members" component="portrait" filters="role: programmer" %}
{% include list.html data="members" component="portrait" filters="role: undergrad" %}
{% include list.html data="members" component="portrait" filters="role: mascot-d" %}
{% include list.html data="members" component="portrait" filters="role: mascot-c" %}

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
  image="images/team/team_2024.PNG"
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
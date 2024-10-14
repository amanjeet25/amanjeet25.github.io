---
---

# Welcome to Food Pro lab’s website. 
# Here, we explore innovative solutions in food science and share our latest research and projects with you.



{% include section.html %}

## Highlights

{% capture text %}

Discover the innovative projects we're working on in food science.

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
  image="images/research1.png"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Explore our published research.

{%
  include button.html
  link="research"
  text="Browse our publications"
  icon="fa-solid fa-arrow-right"
  
  style="bare"
%}


{% endcapture %}

{%
  include feature.html
  image="images/ourresearch.jpg"
  link="research"
  title="Our Research"

  style="bare"
  text=text
%}

{% capture text %}

Get to know the team behind our research and projects.

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
  image="images/team.png"
  link="team"
  title="Our Team"
  flip=true
  text=text
%}

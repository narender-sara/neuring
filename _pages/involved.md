---
title: "Involved"
layout: gridlay
sitemap: false
permalink: /involved/
---

## Get Involved

<div class="jumbotron">
  <h3>Avenues for Collaboration - Research Collaborations:</h3>
  - <strong>Submission:</strong>
    Have an idea for research? Submit a brief paragraph including the following details:
    - Investigator name
    - Email address
    - Institution
    - Title and brief synopsis of the project (1 paragraph)
    - Proposed participants, data sources, and analyses
    
  - <strong>Next steps:</strong> 
    The advisory committee meets monthly to review these data requests, meet formally with submitting investigator to propose best strategy, and pool interested centers to expedite collaborations.
  
  Learning and Dissemination
  - Ongoing participation in Conferences THROUGH WOMEN’S NEUROLOGY TRAINING CURRICULUM 
  - JOINT PROJECTS ACROSS DISCIPLINES TO PROMOTE WOMEN’S NEUROLOGY AS A DISTINCT SUBSEPECIALITY (BOSTON, UCSF, PITT, ETC)
  
</div>

<br>

## Individuals

<div class='jumbotron'>
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}

<div class="col-sm-3">
<img src="../images/{{ member.photo }}" width="100%" style="max-width:250px"/>
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br></i>
</div>

<!-- {% if member.website %}<a href="{{ member.website }}" target="_blank"><i class="fa fa-home fa-2x"></i></a> {% endif %} -->
<!-- {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-2x"></i></a> {% endif %} -->
<!-- {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-2x"></i></a> {% endif %} -->
<!-- {% if member.cv %} <a href="{{ member.cv }}" target="_blank"><i class="ai ai-cv-square ai-2x"></i></a> {% endif %} -->
<!-- {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-2x"></i></a> {% endif %} -->
<!-- {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-2x"></i></a> {% endif %} -->
<!-- </div> -->

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 3 %}

</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd != 0 %}

</div>
{% endif %}
</div>

<br>

## Partners

<div class="jumbotron">
- Industry Partners: Biogen, EMD Serono, Roche Genentech, Novartis, TG Therapeutics
- National Multiple Sclerosis Society (NMSS)
- Women’s Brain Health Rounds
- International Women in Multiple Sclerosis (iWIMS)
- CONSORTIUM OF MS CENTERS
</div>

<br>

## Future Support

<div class="jumbotron">
To ensure the sustainability and growth of our collaborative efforts, we are committed to pursuing diverse funding opportunities that align with our mission. Our goal is to secure financial support that allows us to expand research initiatives, support young investigators, and enhance infrastructure for collaboration.

We plan to apply for grants from national and international funding agencies focused on neuroimmunology, women’s health, and healthcare disparities. By leveraging our established network and track record of impactful research, we aim to present compelling proposals that highlight our unique collaborative model and its potential for advancing knowledge and improving clinical outcomes.

In addition to government grants, we will seek partnerships with industry sponsors, foundations, and philanthropic organizations that share our commitment to advancing women’s health in neuroimmunological diseases. These partnerships will enable us to pursue high-impact studies, develop new technologies, and support initiatives such as biosample collection, neuroimaging, and disparities research.

We also plan to establish a structured mentorship and training program for young investigators within our network, with dedicated funding to support their projects and professional development. This will create a pipeline of skilled researchers prepared to lead the next generation of discoveries in neuroimmunology.
By securing a diverse array of funding sources, we aim to ensure that our network continues to thrive, innovate, and expand, ultimately improving health outcomes for women affected by neuroimmunological diseases.
</div>
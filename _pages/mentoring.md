---
layout: page
title: mentoring
permalink: /mentoring/
description:
nav: true
---

<!-- &nbsp; -->

<hr>

### [dill 🌿 lab ](https://dill-lab.github.io/)

I lead the **[Datasets, Interpretability, Language and Learning](https://dill-lab.github.io/)** (DILL 🌿) Lab at USC.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/dill-selfie.jpg' | relative_url }}" alt="" title="DILL Sep 2022"/>
    </div>
</div>
<div class="caption">
  From R to L: Sayan Ghosh, Ting-Rui Chiang, Jaspreet Ranjit and myself.
</div>
&nbsp;



<hr>

&nbsp;

### interns and student collaborators

I had the pleasure of mentoring and collaborating with several students and interns during my postdoc at AI2, as well as during my PhD.


<div class="projects grid">

  {% assign sorted_projects = site.group | sort: "time" %}
  {% for project in sorted_projects reversed %}
  <div class="grid-item">
    {% if project.redirect %}
    <a href="{{ project.redirect }}" target="_blank">
    {% else %}
    <a href="{{ project.url | relative_url }}">
    {% endif %}
      <div class="card hoverable">
        {% if project.img %}
        <img src="{{ project.img | relative_url }}" alt="project thumbnail">
        {% endif %}
        <div class="card-body">
          <h3 class="card-title text-lowercase">{{ project.title }}</h3>
          <p class="card-text">{{ project.description }}</p>
          {% if project.comentor %}
          <p class="card-text">Co-Mentor: {{ project.comentor }}</p>
          {% endif %}
          {% if project.thesis %}
          <p class="card-text"><a href="{{ project.thesis }}">Thesis</a></p>
          {% endif %}
          <p class="card-text">📅 {{ project.time }}</p>
          <div class="row ml-1 mr-1 p-0">
          </div>
        </div>
      </div>
    </a>
  </div>
{% endfor %}

</div>

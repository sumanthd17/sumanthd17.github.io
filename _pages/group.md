---
layout: page
title: group
permalink: /group/
description:
nav: true
---

&nbsp;

### PhD Students
Starting Fall 2022.


<hr>

### AI2 Interns and Student Collaborators


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
            {% if project.github %}
            <div class="github-icon">
              <div class="icon" data-toggle="tooltip" title="Code Repository">
                <a href="{{ project.github }}" target="_blank"><i class="fab fa-github gh-icon"></i></a>
              </div>
              {% if project.github_stars %}
              <span class="stars" data-toggle="tooltip" title="GitHub Stars">
                <i class="fas fa-star"></i>
                <span id="{{ project.github_stars }}-stars"></span>
              </span>
              {% endif %}
            </div>
            {% endif %}
          </div>
        </div>
      </div>
    </a>
  </div>
{% endfor %}

</div>

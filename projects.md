---
layout: page
title: Projects
---
^{}
<div class="project">
  <h2^{{ project.title }}</h2>
  <img src="{{ site.baseurl }}{{ project.image }}" width="200">
  <a href="{{ project.github }}">GitHub</a> | 
  <a href="{{ project.demo }}">Demo</a>
  {{ project.content }}
</div>
^{}

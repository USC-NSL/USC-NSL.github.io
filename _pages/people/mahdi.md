---
title: "NSL Lab - Mahdi"
layout: personal
permalink: /people/mahdi-alizadeh/
sitemap: false
excerpt: "Personal website of Mahdi"
---
{%- assign data = site.data.people -%}
{%- assign member = data.mahdi -%}

<div class="row">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="22%" style="float: left" />
  <h1>{{ member.name }}</h1>
  <i style="font-size:20px">{{ member.info }}</i><br>

  {% if member.website %}<a href="{{ member.website }}" target="_blank"><i class="fa fa-home fa-3x"></i></a> {% endif %}
  {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-3x"></i></a> {% endif %}
  <!-- {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-3x"></i></a> {% endif %} -->
  <!-- {% if member.cv %} <a href="{{ site.url }}{{ site.baseurl }}/files/{{ member.cv }}" target="_blank"><i class="ai ai-cv-square ai-3x"></i></a> {% endif %} -->
  {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-3x"></i></a> {% endif %}
  {% if member.linkedin %} <a href="{{ member.linkedin }}" target="_blank"><i class="fa fa-linkedin-square fa-3x"></i></a> {% endif %}
  <!-- {% if member.twitter %} <a href="{{ member.twitter }}" target="_blank"><i class="fa fa-twitter-square fa-3x"></i></a> {% endif %} -->
  <!-- {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-3x"></i></a> {% endif %} -->
  <ul style="overflow: hidden">

  {% for education in member.education %}
	<li> {{ education }} </li>
  {% endfor %}

  </ul>
</div>


## Sketch

I am a Ph.D. student in the <a href="https://cs.usc.edu/" data-type="URL" data-id="https://cs.usc.edu/">CS department</a> at the <a href="https://www.usc.edu/">University of Southern California</a>. I am currently a member of <a href="https://nsl.usc.edu/">Networked Systems Lab</a> and very fortunate to be advised by <a href="https://govindan.usc.edu/">Prof. Ramesh Govindan</a>.
Before joining USC, I completed my B.Sc. in <a href="http://ce.sharif.edu/~web/en/">Computer Engineering</a> at the <a href="http://www.en.sharif.edu/">Sharif University of Technology</a> in 2025.


## Work Experience

<p><em>Graduate Research Assistant</em> (Aug 2025 - present) <br>University of Southern California, Los Angeles</p>
<p><em>Software Engineer</em> (Dec 2023 - Aug 2025) <br>Cafe Bazaar, Tehran</p>
<p><em>Research Intern</em> (Jul 2023 - Dec 2023) <br>MPI SWS, Saarbrücken</p>
<p><em>DevOps Engineer</em> (Jul 2022 - Nov 2023) <br>Tapsi, Tehran, Tehran</p>

{% if member.awards %}
## Awards
{% endif %}

{% for award in member.awards %}
<ul style="overflow: hidden">
<li> {{ award }} </li>
</ul>
{% endfor %}


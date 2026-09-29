---
title: "NSL Lab - Arvin"
layout: personal
permalink: /people/arvin-ghavidel/
sitemap: false
excerpt: "Personal website of Pooria"
---
{%- assign data = site.data.people -%}
{%- assign member = data.arvin -%}

<div class="row">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="22%" style="float: left" />
  <h1>{{ member.name }}</h1>
  <i style="font-size:20px">{{ member.info }}</i><br>

  {% if member.website %}<a href="{{ member.website }}" target="_blank"><i class="fa fa-home fa-3x"></i></a> {% endif %}
  {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-3x"></i></a> {% endif %}
  {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-3x"></i></a> {% endif %}
  <!-- {% if member.cv %} <a href="{{ site.url }}{{ site.baseurl }}/files/{{ member.cv }}" target="_blank"><i class="ai ai-cv-square ai-3x"></i></a> {% endif %} -->
  {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-3x"></i></a> {% endif %}
  {% if member.linkedin %} <a href="{{ member.linkedin }}" target="_blank"><i class="fa fa-linkedin-square fa-3x"></i></a> {% endif %}
  {% if member.twitter %} <a href="{{ member.twitter }}" target="_blank"><i class="fa fa-twitter-square fa-3x"></i></a> {% endif %}
  <!-- {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-3x"></i></a> {% endif %} -->
  <ul style="overflow: hidden">

  {% for education in member.education %}
	<li> {{ education }} </li>
  {% endfor %}

  </ul>
</div>

## Sketch

<p>I am a <a href="https://minghsiehece.usc.edu/" data-type="URL" data-id="https://minghsiehece.usc.edu/">ECE</a> Ph.D. student at the <a href="https://www.usc.edu/">University of Southern California</a> and a member of <a href="https://nsl.usc.edu/">Networked Systems Lab</a>, very fortunate to be advised by <a href="https://govindan.usc.edu/">Prof. Ramesh Govindan</a>. My research focus is very broadly on the design of distributed systems and their management. This could either be a focus on <a href="https://dl.acm.org/doi/10.1145/3718958.3750533">how to manage them</a> or <a href="https://dl.acm.org/doi/10.1145/3789240.3829123">why they should be like that</a>. With practicality in mind, I try to combine theoretical methods like convex programming or formal verification to attack these problems.</p>
<p>Before joining USC, I completed my B.Sc. in <a href="http://ee.sharif.edu/~web/en/">Electrical Engineering</a> at the <a href="http://www.en.sharif.edu/">Sharif University of Technology</a> in 2022.</p>
<p>Feel free to contact me via email (I rarely miss them, but please feel free to send reminders if I take more than a few days to respond).</p>

## Work Experience

<p><em>Graduate Research Assistant</em> (Jan. 2023 - present) <br>University of Southern California, Los Angeles, CA</p>
<p><em>Research Intern & Student Researcher</em> (May 2026 - Aug. 2026)<br>Microsoft Research, Redmond, WA<br>Mentors: <a href="https://www.microsoft.com/en-us/research/people/bearzani/">Behnaz Arzani</a>, <a href="https://www.microsoft.com/en-us/research/people/namyarpooria/">Pooria Namyar</a> and <a href="https://www.microsoft.com/en-us/research/people/kmellou/">Konstantina Mellou</a>.</p>

{% if member.awards %}
## Awards
{% endif %}

{% for award in member.awards %}
<ul style="overflow: hidden">
<li> {{ award }} </li>
</ul>
{% endfor %}

## Selected Publications

<div class="publications">

{% bibliography -f people/pooria_selected%}

</div>

## Other Publications

<div class="publications">

{% bibliography -f people/pooria_additional%}

</div>

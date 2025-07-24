---
title: "NSL Lab - Home"
layout: homelay
excerpt: "NSL Lab at University of Southern California."
sitemap: false
permalink: /
---

<h3> About </h3>

<div>

Founded in 2002, our laboratory conducts research on the design and implementation of a wide range of networked computing systems.

</div>

<div markdown="0" id="carousel" class="carousel slide" data-ride="carousel" data-interval="4000" data-pause="hover" >
    <!-- Menu -->
    <ol class="carousel-indicators">
        <li data-target="#carousel" data-slide-to="0" class="active"></li>
        <li data-target="#carousel" data-slide-to="1"></li>
        <li data-target="#carousel" data-slide-to="2"></li>
        <li data-target="#carousel" data-slide-to="3"></li>
        <li data-target="#carousel" data-slide-to="4"></li>
        <li data-target="#carousel" data-slide-to="5"></li>
        <li data-target="#carousel" data-slide-to="6"></li>
        <li data-target="#carousel" data-slide-to="7"></li>
    </ol>

    <!-- Items -->
    <div class="carousel-inner" markdown="0">
        <div class="item active">
            <div class="img-box">
                <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/Xiao_FireLoc.png" alt="Slide 1" />
            </div>
        </div>
        <div class="item">
            <div class="img-box">
                <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/Rajrup_KinectStream.png" alt="Slide 2" />
            </div>
        </div>
        <div class="item">
            <div class="img-box">
                <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/Yao_Cosmic.png" alt="Slide 3" />
            </div>
        </div>
        <div class="item">
            <div class="img-box">
                <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/Christina_RECAP.png" alt="Slide 4" />
            </div>
        </div>
        <div class="item">
            <div class="img-box">
                <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/Fawad_CarMap.png" alt="Slide 5" />
            </div>
        </div>
        <div class="item">
            <div class="img-box">
                <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/Shaoyu_AMoE.png" alt="Slide 6" />
            </div>
        </div>
         <div class="item">
            <div class="img-box">
                <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/Weiwu_Pedestrian.png" alt="Slide 7" />
            </div>
        </div>
        <div class="item">
            <div class="img-box">
                <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/Coulson_Granular.png" alt="Slide 8" />
            </div>
       </div>
    </div>
  <a class="left carousel-control" href="#carousel" role="button" data-slide="prev">
    <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="right carousel-control" href="#carousel" role="button" data-slide="next">
    <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>

<!--
<h3> Recent Papers </h3>

<div class="publications">
{% comment %}
{% bibliography -f papers --max 5 %}
{% endcomment %}
</div>
-->

<h3> Selected Recent Publications </h3>

<div class="publications">
{% bibliography -f papers -q @*[selected=yes]* --max 5 %}
</div>

---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 1
---

See also [Google Scholar](https://scholar.google.com/citations?user=rzBcBq0AAAAJ){:target="\_blank"} and [DBLP](https://dblp.org/pid/208/8581){:target="\_blank"}.

Authors are listed in alphabetical order by last name, unless an asterick(\*) is indicated. [[AMS Statement]](https://www.ams.org/profession/leaders/CultureStatement04.pdf){:target="\_blank"}

<!-- _pages/publications.md -->
<div class="publications">
  
  <h1>conference & journal articles</h1>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[manuscript=false]* %}

</div>

<div class="publications">
  
  <h1>book chapters</h1>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[book=true]* %}

</div>

<div class="publications">
  
  <h1>manuscripts</h1>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[manuscript=true]* %}

</div>

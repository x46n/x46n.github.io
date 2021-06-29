---
layout: archive
title: "Selected Talks"
permalink: /talks/
author_profile: true
---
<!--
## INFORMS Annual Conference, Seattle, WA
- October 2019


## Operations Management Seminar at NYU Stern, New York, NY
- September 2019


## MSOM Annual Conference, Singapore
- June 2019


## POMS Annual Conference, Washington, DC
- May 2019


## UGVR Poster Session at Stanford, Palo Alto, CA
- September 2016
     
-->     

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}


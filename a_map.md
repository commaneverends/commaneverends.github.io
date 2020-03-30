---
layout: page
title: /map
permalink: /map/
---

# places,neverends :round_pushpin:
This is a list of places we love.
touch *:sun_with_face:/:first_quarter_moon_with_face:* below to see details. (in alphabetical order)

<details>
#### days
<ul>
  {% for member in site.data.safespaces-day %}
  <li>
<font color="red"> {{ member.name }} </font> / <font color="yellow"> {{ member.address }} </font> / <font color="gray"> {{ member.website }} </font>
  </li>
{% endfor %}
</ul>
</details>
  

<details>
#### nights
<ul>
{% for member in site.data.safespaces-night %}
  <li>
<font color="blue"> {{ member.name }} </font> / <font color="yellow"> {{ member.address }} </font> / <font color="gray"> {{ member.website }} </font>
  </li>
{% endfor %}
</ul>
</details>

You can also find the location of each place in the map below. (click coinstacks to see places)

<iframe width="100%" height="400px" frameborder="0" allowfullscreen src="https://umap.openstreetmap.co/en/map/placesneverends_2508?scaleControl=true&miniMap=false&scrollWheelZoom=true&zoomControl=true&allowEdit=false&moreControl=true&searchControl=true&tilelayersControl=false&embedControl=false&datalayersControl=expanded&onLoadPanel=undefined&captionBar=true&datalayers=5282%2C5281&fullscreenControl=false&locateControl=true&editinosmControl=false&measureControl=false#17/52.51335/13.45708"></iframe>

Contact us if you have any suggestion. <a href="https://commaneverends.github.io/contact" target="_blank">:speech_balloon:</a>
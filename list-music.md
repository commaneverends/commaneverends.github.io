<h3><font color="white"> artist </font> / <font color="white"> genre </font></h> <p>(in alphabetical order)

<ul>
{% for member in site.data.musicform %}
  <li>
      <font color="red">{{ member.item }}</font> <font color="yellow">{{ member.genre }}</font> 
  </li>
{% endfor %}
</ul>
---
layout: page
title: /film
permalink: /film/
---
<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto+Condensed&display=swap');

.bodycontents {background-color: #ABC9FF;
}
.maintext {margin: 10px 10px 20px 10px;
}

h2 {color:#4C39CA; font-size: 24px; font-family: 'Roboto Condensed', sans-serif;
}
     
</style>

<div class="bodycontents">
<div class="maintext">
<h2>film, neverends </h2>
     
Look! We created a global map to emphasize the diversity of FLINTA* film directors.<br/>
To see them, click the coinstacks in the map. <br/>

<iframe width="100%" height="400px" frameborder="0" allowfullscreen src="https://umap.openstreetmap.co/en/map/filmneverends_2842?scaleControl=true&miniMap=false&scrollWheelZoom=true&zoomControl=true&allowEdit=false&moreControl=true&searchControl=true&tilelayersControl=false&embedControl=false&datalayersControl=expanded&onLoadPanel=undefined&captionBar=true&datalayers=5282%2C5281&fullscreenControl=false&locateControl=true&editinosmControl=false&measureControl=false#5/1.911/-64.468"></iframe>
</div>


---
Here you can find FLINTA* directors and some of their masterpieces.<br/>
<iframe style="border-style: none; width:100%; height:300px;" src="https://commaneverends.github.io/table_film/index.html" frameBorder="0"></iframe>

</div>


---


<font color="red"> Send us your fav films made by FLINTA* directors. </font> 

<script data-cfasync="false" type="text/javascript" src="form-submission-handler.js"></script>

<form class="gform" method="POST" id="car_request_form" role="form" action="https://script.google.com/macros/s/AKfycbw4uqE9OpRTnm_7eIdmPS7VLADGdQI6l6Tn0ueX/exec" target="after" onsubmit="close()">
  
<form>
  <input type="text" id="name" name="director" placeholder="director name:" autocomplete="off">
  <input type="text" id="film" name="filmtitle" placeholder="film title_year:" autocomplete="off">
  <input type="text" id="email" name="subscription" placeholder="If you want further updates: write your email address here" autocomplete="off">  
  <input type="submit" value="[ submit ]" onclick="displayThanks()">  
 
</form>

<iframe id="after" name="after" frameborder="0" onmousewheel="" width="100%" height="0.1" style="background: transparent; border: none;">
</iframe>

<div style="display:none" class="thanks_message">
<span id="span_thanks"> Thanks for your support. See you again! </span>
</div>

<script>
function close() {
    document.querySelector('#after').addEventListener('load', function() {
        window.close();
    });
  
}
function displayThanks() {
   var span_Text = document.getElementById("span_thanks").innerText;
   alert (span_Text);
}
</script>


<a href="#" target="_blank"> other interesting links (- in preparation -) </a>

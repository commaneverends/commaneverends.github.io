---
layout: page
title: /literature
permalink: /literature/
---
<style>
   
h2 {color:#4C39CA; font-size: 24px;
    }
    
.bodycontents {background-color: #FF9C01;

    }
.maintext {margin: 10px 10px 20px 10px;}

.div-book-month-title{
    font-family: 'Saira Stencil One', cursive;
    font-size: 24px;
    margin: 0px;
}

</style>
  
  
<div class="bodycontents">
<div class="bookmonth" left="1px;" right="0px;"><iframe width="100%" height="440px;" margin="5px;" frameborder="0" allowfullscreen src="https://commaneverends.github.io/commasmonth/2021-03-book.html"></iframe>..<br/></div>

<div class="maintext">
<h2> Story, neverends </h2>
Here you can find FLINTA* writers. Visit our <span style="font-weight: bold; font-style: italic;"><a href="https://www.goodreads.com/user/show/104617976-commaneverends" target="_blank"> Goodreads account </a></span> and get inspired by the wide range of FLINTA* intellectualism.

<h2>Our Goodread Genres</h2>
<em>fiction</em> / <em>nonfiction</em> / <em>feminism</em> / <em>gender studies</em> / <em>autobiographies</em> / <em>graphic-novel</em> / <em>philosphy</em> / <em>art</em> / <em>poetry</em> / <em>psychology</em> / <em>sci-fi</em>
&nbsp;
</div>

</div>

---
         
<font color='yellow'> Send us your fav books, any kinds of FLINTA* authors/writers. </font> 

<script data-cfasync="false" type="text/javascript" src="form-submission-handler.js"></script>

<form class="gform" method="POST" id="car_request_form" role="form" action="https://script.google.com/macros/s/AKfycbxZYxmzxIl79dR-rQUCo9aGwTDu6YRiD4gfXFWv5w/exec" target="after" onsubmit="close()">
  
<form>
  <input type="text" id="name" name="authorname" placeholder="author name:" autocomplete="off">
  <input type="text" id="title" name="booktitle" placeholder="title of the book:" autocomplete="off">
  <input type="text" id="genre" name="bookgenre" placeholder="genre of the book: e.g. fiction, nonfiction, feminism, gender studies, autobiographies, graphic-novel, philosphy, art, poetry, psychology, sci-fi, other" autocomplete="off">
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

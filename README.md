# achondroplasia
<!DOCTYPE html>
<html>
<head>
<style>
div.container {
    width: 100%;
    border: 1px solid gray;
}

header, footer {
    padding: 5em;
    color: white;
    background-color: steelblue;
    clear: left;
    text-align: center;
}

nav {
    float: left;
    max-width: 160px;
    margin: 0;
    padding: 2em;
}

nav ul {
	
    list-style-type: none;
    padding: 0;
}
   
nav ul a {
	color: grey;
    text-decoration: none;
}

article {
    margin-left: 170px;
    border-left: 1px solid gray;
    padding: 1em;
    overflow: hidden;
}
</style>
</head>
<body>

<div class="container">

<header>
   <h1>Achondroplasia</h1>
</header>
  
<nav>
  <ul>
    <li><a href="#">physical deformity</a></li>
    <li><a href="#">short stature</a></li>
    <li><a href="#">enlarged head</a></li>
  </ul>
</nav>

<article>
  <h1>London</h1>
  <p>London is the capital city of England. It is the most populous city in the  United Kingdom, with a metropolitan area of over 13 million inhabitants.</p>
  <p>Standing on the River Thames, London has been a major settlement for two millennia, its history going back to its founding by the Romans, who named it Londinium.</p>
</article>

<footer>Copyright &copy; W3Schools.com</footer>

<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<body>

<h2 class=""></h2>

<div class="w3-content w3-display-container">
  <img class="mySlides" src="http://i.dailymail.co.uk/i/pix/2009/06/09/article-1191823-054638A7000005DC-350_634x362.jpg" style="width:700px;">
  <img class="mySlides" src="http://www.guinnessworldrecords.com/Images/Shortest-married-couple-London-walking_tcm25-451497.jpg" style="width:700px;">
  <img class="mySlides" src="https://i.ytimg.com/vi/ZSoKKexKz2g/maxresdefault.jpg" style="width:700px;">
  <img class="mySlides" src="http://i.dailymail.co.uk/i/pix/2012/05/04/article-2139488-12ED4B2F000005DC-205_634x326.jpg" style="width:700px;">
  <button class="w3-button w3-black w3-display-left" onclick="plusDivs(-1)">&#10094;</button>
  <button class="w3-button w3-black w3-display-right" onclick="plusDivs(1)">&#10095;</button>
</div>

<script>
var slideIndex = 1;
showDivs(slideIndex);

function plusDivs(n) {
  showDivs(slideIndex += n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  if (n > x.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = x.length}
  for (i = 0; i < x.length; i++) {
     x[i].style.display = "none";  
  }
  x[slideIndex-1].style.display = "block";  
}
</script>

</body>
</html>

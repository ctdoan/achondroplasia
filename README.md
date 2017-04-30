# Diminutive Warriors of Achondroplasia Recovery Foundation

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
    background-color: powderblue;
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
    margin-left: 350px;
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
  <img src="http://genetics4medics.com/uploads/3/4/3/7/34378110/5935279_orig.png" style="width:300px;">
  <ul>
    <li><a href="#">physical deformity</a></li>
    <li><a href="#">short stature</a></li>
    <li><a href="#">enlarged head</a></li>
  </ul>
</nav>

<article>
  <h1>Background Information</h1>
  <p>Achondroplasia is an autosomal dominant genetic disease that results in short limbs due to a mutation in the FGFR3 gene of chromosome 4, which  can be inherited from (a) parent(s) or obtained spontaneously. If occurring spontaneously, the mutation will occur in one of the parents’ haploid gametes before the parents conceive, thus causing the child to inherit the disease. The mutation of the FGFR3 gene causes short limbs by preventing cartilage, a body tissue, from forming into bone while a baby is growing. The lack of ability to convert cartilage to bone results in a short stature, and prevents regular growth of bones.</p>
</article>

<article>
	<h2>Symptoms</h2>
	<ul>A large head with a prominent forehead</ul>
	<ul>Flattened bridge of the nose</ul>
	<ul>Protruding jaw</ul>
	<ul>Crowded and misaligned teeth</ul>
	<ul>Curvature of the spine</ul>
	<ul>Bowed legs</ul>
	<ul>Flat, short, broad feet</ul>
	<ul>Double-jointedness</ul>
	<ul>Late development of motor skills (such as standing up or walking)</ul>
	<ul>Breathing problems</ul>
	<ul>Stiffness or arthritis</ul>
	<ul>Leg numbness</ul>
	<ul>Back pain</ul>
	</article>

<footer>
	<p>DONATE TO D.W.A.R.F. TODAY!</p>
	<p>(Diminutive Warriors of Achondroplasia Recovery Foundation)</p>
</footer>

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

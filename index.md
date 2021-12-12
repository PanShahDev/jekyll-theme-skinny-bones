<html>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://www.w3schools.com/lib/w3-theme-black.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<body id="myPage">

<style>
body, html {
  height: 100%;
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

.hero-image {
  background-image:  url("https://serving.photos.photobox.com/010393455ff5cb4f6366044b0286df7e8e1e39d8fea4194c961a795511fadfdc236e7dca.jpg");
  height: 50%;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}

.hero-text {
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
}

.hero-text button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 10px 25px;
  color: black;
  background-color: #ddd;
  text-align: center;
  cursor: pointer;
}

.hero-text button:hover {
  background-color: #555;
  color: white;
}
</style>



<!-- Navbar -->
<div class="w3-top">
 <div class="w3-bar w3-theme-d2 w3-left-align">

  <a href="#" class="w3-bar-item w3-button w3-teal"><i class="fa fa-home w3-margin-right"></i>Home</a>
  <a href="#team" class="w3-bar-item w3-button w3-hide-small w3-hover-white">About</a>

  <a href="#contact" class="w3-bar-item w3-button w3-hide-small w3-hover-white">Contact</a>
    <div class="w3-dropdown-hover w3-hide-small">

  </div>

 </div>

  <!-- Navbar on small screens -->
  <div id="navDemo" class="w3-bar-block w3-theme-d2 w3-hide w3-hide-large w3-hide-medium">
    <a href="#team" class="w3-bar-item w3-button">About</a>

    <a href="#contact" class="w3-bar-item w3-button">Contact</a>

  </div>
</div>

<!-- Image Header -->

 
<div class="hero-image">

</div>
  <div class="w3-container w3-display-bottomleft w3-margin-bottom">  

  </div>


<!-- Modal -->
<div id="id01" class="w3-modal">
  <div class="w3-modal-content w3-card-4 w3-animate-top">
    <header class="w3-container w3-teal w3-display-container"> 
      <span onclick="document.getElementById('id01').style.display='none'" class="w3-button w3-teal w3-display-topright"><i class="fa fa-remove"></i></span>
      <h4>Oh snap! We just showed you a modal..</h4>
      <h5>Because we can <i class="fa fa-smile-o"></i></h5>
    </header>
    <div class="w3-container">
      <p>Cool huh? Ok, enough teasing around..</p>
      <p>Go to our <a class="w3-text-teal" href="/w3css/default.asp">W3.CSS Tutorial</a> to learn more!</p>
    </div>
    <footer class="w3-container w3-teal">
      <p>Modal footer</p>
    </footer>
  </div>
</div>

<!-- Team Container -->
<div class="w3-container w3-padding-64 w3-center" id="team">
<h2>Nice to Meet You.</h2>
<p>Welcome to my page. My name is Pan Shahbazi (short for Paniz Shahbazian); an Iranian-American, LA-based jack-of-all-trades. I currently work as the DOO of a company that brings new life to the world of hearing protection and music-related tech. I recently worked on an app ("Ear Scanner") that was released to the app store, which enables users to get a full scan of their ears at home (basically, ear molds without all the goop and having to travel to an audiologist). Feel free to check it out <a href="https://apps.apple.com/us/app/ear-scanner/id1557053042">here.</a></p><p>

I'm also full-stack web-developer, with an extensive knowledge in UI/UX design. I'm fascinated by the possibilities of AI and what quantum computing can bring to our future. Follow me on my socials for more (linked at the bottom of this page).
</p>




</div>

<div class="w3-container w3-padding-64 w3-theme-l5" id="contact">
  <div class="w3-row">
    <div class="w3-col m5">
    <div class="w3-padding-16"><span class="w3-xlarge w3-border-teal w3-bottombar">Contact Me</span></div>

      <p><i class="fa fa-map-marker w3-text-teal w3-xlarge"></i> Los Angeles, CA</p>
     <!-- <p><i class="fa fa-phone w3-text-teal w3-xlarge"></i>  +00 1515151515</p> -->
      <p><i class="fa fa-envelope-o w3-text-teal w3-xlarge"></i> me@panshahbazi.com</p>
        <a class="w3-button w3-large w3-teal" href="https://facebook.com/PanShahbazi" title="Facebook"><i class="fa fa-facebook"></i></a> Facebook<p>
  <a class="w3-button w3-large w3-teal" href="https://twitter.com/PanShahbazi" title="Twitter"><i class="fa fa-twitter"></i></a> Twitter<p>
  <a class="w3-button w3-large w3-teal" href="https://instagram.com/PanShahbazi" title="IG"><i class="fa fa-instagram"></i></a> Instagram<p>
  <a class="w3-button w3-large w3-teal w3-hide-small" href="https://linkedin.com/PanShahbazi" title="Linkedin"><i class="fa fa-linkedin"></i></a> LinkedIn
   
    <div class="w3-col m7">
      <form class="w3-container w3-card-4 w3-padding-16 w3-white" action="/action_page.php" target="_blank">
      <div class="w3-section">      
  <script src="https://apps.elfsight.com/p/platform.js" defer></script>
<div class="elfsight-app-1799076e-d996-443f-a7e0-c0b486c0d2f3"></div>
    </div>
  </div>
</div>

<!-- Image of location/map -->

<!-- Footer -->
<footer class="w3-container w3-padding-32 w3-theme-d1 w3-center">
  <h4>See You Later.</h4>



  <div style="position:relative;bottom:100px;z-index:1;" class="w3-tooltip w3-right">
    <span class="w3-text w3-padding w3-teal w3-hide-small">Go To Top</span>   
    <a class="w3-button w3-theme" href="#myPage"><span class="w3-xlarge">
    <i class="fa fa-chevron-circle-up"></i></span></a>
  </div>
</footer>

<script>
// Script for side navigation
function w3_open() {
  var x = document.getElementById("mySidebar");
  x.style.width = "300px";
  x.style.paddingTop = "10%";
  x.style.display = "block";
}

// Close side navigation
function w3_close() {
  document.getElementById("mySidebar").style.display = "none";
}

// Used to toggle the menu on smaller screens when clicking on the menu button
function openNav() {
  var x = document.getElementById("navDemo");
  if (x.className.indexOf("w3-show") == -1) {
    x.className += " w3-show";
  } else { 
    x.className = x.className.replace(" w3-show", "");
  }
}
</script>

</body>
</html>
---
layout: archive
permalink: /
title: "Latest Posts"
title: "Welcome"
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
  <img src="https://i.ibb.co/S6JGSdL/Untitled-design-3.png">
{% endfor %}
</div><!-- /.tiles -->

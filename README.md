
<!DOCTYPE html>
<html>
<title>Arpan Pal</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Cantarell">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body, h1,h2,h3,h4,h5,h6 {font-family: "Cantarell", sans-serif}
.w3-row-padding img {margin-bottom: 12px}
/* Set the width of the sidebar to 120px */
.w3-sidebar {width: 120px;background: #222;}
/* Add a left margin to the "page content" that matches the width of the sidebar (120px) */
#main {margin-left: 120px}
/* Remove margins from "page content" on small screens */
@media only screen and (max-width: 600px) {#main {margin-left: 0}}
</style>
<body class="w3-black">

<!-- Icon Bar (Sidebar - hidden on small screens) -->
<nav class="w3-sidebar w3-bar-block w3-small w3-hide-small w3-center">
  <!-- Avatar image in top left corner -->
<!--
<img src="navbarim/F2_Cayley_Graph.png" style="width:100%">
-->
 
  <a href="#" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-home w3-xxlarge"></i>
    <p>HOME</p>
  </a>

  <a href="#teaching" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-pencil w3-xxlarge"></i>
    <p>TEACHING</p>
  </a>
  <a href="#contact" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-envelope w3-xxlarge"></i>
    <p>CONTACT</p>
  </a>
   <a href="#about" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-user w3-xxlarge"></i>
    <p>ABOUT ME</p>
  </a>
   <a href="#links" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-link w3-xxlarge"></i>
    <p>LINKS</p>
  </a>
</nav>

<!-- Navbar on small screens (Hidden on medium and large screens) -->
<div class="w3-top w3-hide-large w3-hide-medium" id="myNavbar">
  <div class="w3-bar w3-black w3-opacity w3-hover-opacity-off w3-center w3-small">
    <a href="#" class="w3-bar-item w3-button" style="width:25% !important">HOME</a>
    <a href="#teaching" class="w3-bar-item w3-button" style="width:25% !important">TEACHING</a>
    <a href="#contact" class="w3-bar-item w3-button" style="width:25% !important">CONTACT</a>
     <a href="#about" class="w3-bar-item w3-button" style="width:25% !important">ABOUT ME</a>
    <a href="#links" class="w3-bar-item w3-button" style="width:25% !important">LINKS</a>
  </div>
</div>

<!-- Page Content -->
<div class="w3-padding-large" id="main">
  <!-- Header/Home -->
  <header class="w3-container w3-padding-32 w3-center w3-black" id="home">
    <h1 class="w3-xxlarge"><span class="w3-hide-small">Arpan</span> Pal </h1>
    <p>Mathematics PhD student</p>
    <img src="Myphoto1.jpg" alt="A picture of me" class="w3-image" width="480" height="500">
  </header>

  <!-- About Section -->
     <div class="w3-content w3-justify w3-text-grey w3-padding-64" id="about">
 <h2 class="w3-text-light-grey">About Me</h2>
    <hr style="width:200px" class="w3-opacity">
    <p>I am fourth year PhD student at the Department of Mathematics, Texas A&M University. I am working under the supervision of <a href=https://www.math.tamu.edu/~jml/index.html> Prof. JM Landsberg.</a> My area of interest is in Geometric Complexity Theory. </p> 
<button onclick="myAccFunc('Demo2')" class="w3-padding-16 w3-theme w3-button w3-block w3-left-align"><h3 class="w3-text-light-grey">CV</h3></button>
<div id="Demo2" class="w3-hide">
  <a href="CV.pdf" class="w3-button w3-block w3-left-align">View CV here.</a>
<div id="Demo3" class="w3-hide w3-black">
  <div class="w3-container">
    <p>Accordion with Images:</p>
    <img src="/w3images/fjords.jpg" style="width:30%;" class="w3-animate-zoom">
    <p>Trolltunga, Norway</p>
  </div>
</div>    
  <!-- End About Section -->
  </div>
  
  <!-- Teaching -->
   <div class="w3-padding-64 w3-content w3-text-grey" id="teaching">
    <h2 class="w3-text-light-grey">Teaching</h2>
    <hr style="width:200px" class="w3-opacity">
    <button class="w3-padding-16 w3-theme w3-button w3-block w3-left-align"><h3 class="w3-text-light-grey">Current</h3></button>
    <div class="w3-container w3-text-grey">
    Research Assistant
    </div>
    <button onclick="myAccFunc('Past')" class="w3-padding-16 w3-theme w3-button w3-block w3-left-align"><h3 class="w3-text-light-grey">Past</h3></button>
<div id="Past" class="w3-hide w3-black">
  <div class="w3-container w3-text-grey">
  <a href="Teaching/Spring2020/142_505_sp2020.html" class="w3-button w3-block w3-left-align">Spring 2020: Math 142 Sec 505, Instructor of Record.</a>
  <a href="https://www.math.tamu.edu/courses/math152/" class="w3-button w3-block w3-left-align">Fall 2019: Math 152, for sections 508,510,511, Recitation.</a>
  <a href="https://www.math.tamu.edu/graduate/phd/quals.html" class="w3-button w3-block w3-left-align">Summer-II 2019: Was TA for Algebra Qual Prep class.</a>
  <a href="https://www.math.tamu.edu/courses/math148/" class="w3-button w3-block w3-left-align">Spring 2019: Math 148, for sections 501,502,503, Recitation.</a>
  <a href="https://www.math.tamu.edu/courses/math151/" class="w3-button w3-block w3-left-align">Fall 2018: Math 151, for sections 570,571,572, Recitation.</a>
  <a href="https://www.math.tamu.edu/courses/math141/" class="w3-button w3-block w3-left-align">Summer-I 2018: Math 141, Grader.</a>
  <a href="https://www.math.tamu.edu/courses/math407/" class="w3-button w3-block w3-left-align">Spring 2018: Math 407, Grader.</a>
  <a href="https://www.math.tamu.edu/courses/math415/" class="w3-button w3-block w3-left-align">Fall 2017: Math 415, Grader.</a>
  </div>
</div>  
 
    
  <!-- End Teaching Section -->
  </div>

  <!-- Contact Section -->
  <div class="w3-padding-64 w3-content w3-text-grey" id="contact">
    <h2 class="w3-text-light-grey">Contact Me</h2>
    <hr style="width:200px" class="w3-opacity">
    
    
<button onclick="myAccFunc('Office')" class="w3-padding-16 w3-theme w3-button w3-block w3-left-align"><h3 class="w3-text-light-grey"><i class="fa fa-map-marker fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Office</h3></button>
<div id="Office" class="w3-hide">
  <div class="w3-container">
  <h4 class="w3-text-light-grey">Blocker 625X</h4>
 <p>Click <a href="http://aggiemap.tamu.edu?bldg=0524">here</a> to see the Blocker building on Aggie Map. </p>
   <hr style="width:100px" class="w3-opacity">
    
    </p>
  </div>
</div>
<button onclick="myAccFunc('Email')" class="w3-padding-16 w3-theme w3-button w3-block w3-left-align"><h3 class="w3-text-light-grey"><i class="fa fa-envelope fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Email</h3></button>
<div id="Email" class="w3-hide">
  <div class="w3-container">
  <h4 class="w3-text-light-grey">
  <script type="text/javascript">
<!-- Begin
user = "arpan";
domain = "tamu.edu";
document.write('<a href=\"mailto:' + user + '@' + domain + '\">' + 
			user + '@' + domain + '</a>');
// End -->
</script>
<p><script type="text/javascript">
<!-- Begin
user = "arpantamu";
domain = "tamu.edu";
document.write('<a href=\"mailto:' + user + '@' + domain + '\">' + 
			user + '@' + domain + '</a>');
// End -->
</script></p>
<p><script type="text/javascript">
<!-- Begin
user = "arpantamu";
domain = "math.tamu.edu";
document.write('<a href=\"mailto:' + user + '@' + domain + '\">' + 
			user + '@' + domain + '</a>');
// End -->
</script></p>
<p>Here is my permanent email address. Although I discourage its use.</p>
<p><script type="text/javascript">
<!-- Begin
user = "arpan.sanju";
domain = "gmail.com";
document.write('<a href=\"mailto:' + user + '@' + domain + '\">' + 
			user + '@' + domain + '</a>');
// End -->
</script></p>
  </div>
</div>
<!--
<button onclick="myAccFunc('Skype')" class="w3-padding-16 w3-theme w3-button w3-block w3-left-align"><h3 class="w3-text-light-grey"><i class="fa fa-skype fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Skype</h3></button>
<div id="Skype" class="w3-hide">
  <div class="w3-container">
  <h4 class="w3-text-light-grey">ID:  amanda.hoisington</h4>
 <p>Click <a href="https://www.skype.com/en/download">here</a> to download Skype. </p>
  
  </div>
</div>
-->
 
      <!-- End Contact Section -->
 </div>
    
    <!-- Links Section -->
     <div class="w3-padding-64 w3-content w3-text-grey" id="links">
   <h2 class="w3-text-light-grey">Links</h2>
    <hr style="width:200px" class="w3-opacity">
	<p><a href="https://www.math.tamu.edu/">Math Department</a></p>
    <p></p>
    <p></p>
    <p></p>
    <p></p>
    <p></p>
    <p></p>
    <p></p>
    <p></p>
    <!-- End Links Section -->
    </div>
    

 

  
    <!-- Footer -->
  <footer class="w3-content w3-padding-64 w3-text-grey w3-xlarge">
    <p class="w3-medium">Powered by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank" class="w3-hover-text-green">w3.css</a></p>
  <!-- End footer -->
  </footer>

<!-- END PAGE CONTENT -->
</div>
<script>
function myAccFunc(id) {
    var x = document.getElementById(id);
    if (x.className.indexOf("w3-show") == -1) {
        x.className += " w3-show";
    } else { 
        x.className = x.className.replace(" w3-show", "");
    }
}
</script>
</body>
</html>


# 1337spencer.github.io
Project 2:Spencer Tomlinson
<!DOCTYPE html>
<html lang="en">
<head>
<title>New</title>
<meta charset="utf-8">
<link rel="stylesheet" href="STperformance.css">
</head>
<body>
<header>
 <h1><img src="carlogo.jpg.jpg" alt="the logo" width = "1900" height="250" ></h1>
</header>
<nav>
  <a href="home.html">Home</a> &nbsp;
  <a href="class.html">classes</a> &nbsp;
  <a href="activities.html">activities</a> &nbsp;
  <a href="setup.html">Reservations</a>&nbsp;
</nav>
<main>
 <h2>One stop shop for any enthusiest</h2>

 <p><span class="resort"> ST Performance park</span> offers many different classes and tutorials to help you or a loved one learn computer and technologies to improve lifes tasks by doing them online or have a better basic understanding for personal use.</p>
 <ul>
  <li>Self and touchless car washes along with detailers</li>
  <li>On site mechanics</li>
  <li>Pay by the hour lifts and tools.</li>
  <li>Car Storage</li>
  <li>Race licensing and training</li>
 </ul>



<h2> About us</h2>
<p><span class="resort">St Performance</span> is number one in service and experience with an amazing amount of time and effort put into the selection of all staff and products used.

 <ul>
  <li>For Car Enthusiest</li>
  <li>For the community</li>
  <li>Proper intructors and mechanics</li>
  <li>committed to providing the best overall experience</li>
  <li>Best detailers around</li>
<br /><br />
<div id="container">
	<ul>
      	 <li><img src="line.jpg" width="604" height="453" /></li>
         <li><img src="Gtr.jpg" width="604" height="453" /></li>
         <li><img src="camaro.jpg" width="604" height="453" /></li>
      </ul>
      <span class="button prevButton"></span>
      <span class="button nextButton"></span>
</div>


<script src="../jquery-1.4.2.min.js"></script>

<script>
$(window).load(function(){
		var pages = $('#container li'), current=0;
		var currentPage,nextPage;

('container .button').click(function(){
currentPage= pages.eq(current);
if($(this).hasClass('prevButton'))
			{

if (current <= 0)
					current=pages.length-1;
				else
					current=current-1;
			}
			else
			{
				if (current >= pages.length-1)
					current=0;
				else
					current=current+1;
			}
			nextPage = pages.eq(current);	
			currentPage.hide();	
			nextPage.show();		
		});
});

</script>
 </ul> 



<div>
<br>
<br>
<br>
<h3>Contact info</h3>
<span class="resort">St Perforance</span><br>
<span id="content">0000 Spencer Road<br>
Indianapolis,IN 46077<br><br>
phone:555-555-5555</span id="content"><hr>
</div>
<footer><br>
<small><i>Copyright &copy; 2018 Spencer Tomlinson</i></small><br>
 <a href="seniornet.com">Stperformace.com</a>
</footer>
</body>

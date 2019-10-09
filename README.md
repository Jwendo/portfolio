## Welcome to GitHub Pages

<!DOCTYPE html>
<html lang="en" >

<head>
  <meta charset="UTF-8">
  <title>Portfolio Wendo Joyce</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  
  <link rel='stylesheet' href='https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.5.2/animate.min.css'>

  <link rel="stylesheet" href="css/style.css">
	<style>
		/* Style the body and html */
body,
html {
    width: 100%;
    height: 100%;
	font-family: "Lato","Helvetica Neue",Helvetica,Arial,sans-serif;
}
/* Style the container div */
.container{
	width:100%;
	margin: 0, auto;
	}
/* Add a black background color to the top navigation */
.topnav {
    background-color: #333;
    overflow: hidden;
}
/* Style the links inside the navigation bar */
.topnav a {
	float:left;
    display: inline-block;
    color: #f2f2f2;
    text-align: center;
    padding: 14px 18px;
    text-decoration: none;
    font-size: 17px;
}
/* Change the color of links on hover */
.topnav a:hover {
    background-color: #ddd;
    color: black;
    text-decoration:none;
}
/* Hide the link that should open and close the topnav on small screens */
.topnav .icon {
    display: none;
}
/* When the screen is less than 600 pixels wide, hide all links, except for the first one ("Home").*/
@media screen and (max-width: 600px) {
  .topnav a:not(:first-child) {display: none;}
  .topnav a.icon {
    float: right;
    display: block;
  }
}
/* The "responsive" class is added to the topnav with JavaScript when the user clicks on the icon. 
This class makes the topnav look good on small screens (display the links vertically instead of horizontally) */
@media screen and (max-width: 600px) {
  .topnav.responsive {position: relative;}
  .topnav.responsive a.icon {
    position: absolute;
    right: 0;
    top: 0;
  }
  .topnav.responsive a {
    float: none;
    display: block;
    text-align: left;
  }
}
/*Banner div styles here*/
.banner{
		margin: 0, auto;
	
}
 /*intro-header div styles-one with laptop background*/
 .intro-header {
    padding-top: 10px;
    padding-bottom: 10px;
    text-align: center;
    color: #f8f8f8;
    background: url(http://leblogdecarlos.com/wp-content/uploads/2015/06/Laptop_Pingpong.jpg) no-repeat center center;
    background-size: cover;
}
/*intro-message div styles*/
.intro-message {
    position: relative;
    padding-top: 2%;
    padding-bottom: 2%;
}
 /*intro-message h1-Joyce Wendo*/
 .intro-message > h1 {
    text-shadow: 2px 2px 3px rgba(0,0,0,0.6);
    font-size: 5em;
}
 /*intro-message h3-Frontend Web Developer-css is a link in this case*/
.intro-message > a {
  text-shadow: 2px 2px 3px rgba(0,0,0,0.6);
  text-decoration:none;
  font-size:40px;
  }
.intro-message > a:hover {
  text-decoration:none;
  }
 
 /*social buttons */
ul.intro-social-buttons > li {
        background-color:#333333;
		display:inline-block;
		margin-bottom: 10px;
		border-radius: 5px;
        padding: 0;
		
    }
 /*css for dividing line */
.intro-divider {
    width: 700px;
    border-top: 1px solid #f8f8f8;
    border-bottom: 1px solid rgba(0,0,0,0.2);
}
/*--about text styles--*/
#about{
	background-color:skyblue;
	margin: 0, auto;
}
#about h4{
	color:black;
	text-align:center;
}
	
#about p{
	color:black;
	margin: auto;
	text-align:center;
}
	
#about img{
width:250px;
border: 2px solid #ddd;
padding: 3px;
border-radius: 50%;
display: block;
margin: auto;
}	
img:hover {
    box-shadow: 0 0 3px 2px rgba(0, 140, 186, 0.5);
}
img {
    max-width: 100%;
    height: auto;
}
/*--about styles end here--*/
/*portfolio css*/
.content-portfolio {
  background-color: black;
  padding:2px;
  }
 .content-portfolio h2 {
   font-size: 2em;
   text-align: center;
   color:white;
   margin-top: 20px;
   padding:15px 20px 15px 0%;
   text-transform:uppercase;
   	font-family: 'Titillium Web', sans-serif;
    }
.content-portfolio .col-sm-6{
  margin: 20px auto;
  padding: 5px 10px;
}
/*------ Thumb css -------*/
.thumb {
  margin: auto;
  padding-left: 0px; 
  padding-right: 0px;
  }
.thumb img {
   width:400px;
   height: 300px;
   opacity: 1;
   border: 2px solid #ddd;
   padding: 2px;
   display: block;
   margin: auto;
 }
 /*back to top button styles*/
 
 #myBtn {
  display: none;
  position: fixed;
  bottom: 10px;
  right: 30px;
  z-index: 99;
  border: none;
  outline: none;
  background-color: yellow;
  color: orange;
  cursor: pointer;
  padding: 15px;
  border-radius: 10px;
}
 #myBtn:hover {
  background-color: #555;
}
 
/*responsive design using media queries for screens with a width between 600px-1200px*/
@media(min-width: 600px),
		(max-width: 1200){
.intro-message > a {
  text-decoration:none;
  font-size:2em;
  text-transform:uppercase;
  }  
  
.intro-header {
    padding-top: 1px;
    padding-bottom: 1px;
    background: url(http://leblogdecarlos.com/wp-content/uploads/2015/06/Laptop_Pingpong.jpg) no-repeat center center;
    background-size: cover;
}
.intro-message {
        padding-bottom: 0%;
    }
.intro-message > h1 {
        font-size: 5em;
    }
			
ul.intro-social-buttons > li {
        display: inline-block;
		border-radius: 5px;
		text-align: center;
		text-decoration: none;
		font-size: 2em;
	}
		
.intro-divider {
        width: 100%;
    }
		
 }
  
/*responsive design using media queries for screens with a width of 768px and below*/  
@media (max-width: 600px){
.intro-message > a {
  text-decoration:none;
  font-size:1.2em;
  text-transform:uppercase;
  }   
.intro-header {
    padding-top: 1px;
    padding-bottom: 1px;
    background: url(http://leblogdecarlos.com/wp-content/uploads/2015/06/Laptop_Pingpong.jpg) no-repeat center center;
    background-size: cover;
}
.intro-message {
        padding-bottom: 0%;
    }
.intro-message > h1 {
        font-size: 2em;
    }
	
ul.intro-social-buttons > li {
    display: block;
	font-size: 0.8em;
	border: 2px solid;
    margin: 3px auto;
	}
	
ul.intro-social-buttons > li:last-child {
    margin-bottom: 0;
    }
.intro-divider {
        width: 100%;
    }
	
.content-portfolio h2 {
   font-size: 1em;
   text-align: center;
   color:white;
   margin-top: 10px;
   padding:5px 10px 5px 10px;
   text-transform:uppercase;
   font-family: 'Titillium Web', sans-serif;
   }
   
#about h4{
	color:white;
	font-size:1.2em;
	margin: auto;
}
	
#about p{
	color:black;
	margin: auto;
	text-align:center;
}
	
#about img{
width:150px;
border: 2px solid #ddd;
padding: 2px;
border-radius: 50%;
display: block;
margin: auto;
}
.thumb {
  display:block;
  width:100%;
  }
	
#myBtn {
  position: fixed;
  bottom: 20px;
  right: 25px;
  z-index: 99;
  border: none;
  outline: none;
  background-color: yellow;
  color: orange;
  cursor: pointer;
  padding: 5px;
  border-radius: 10px;
}
		
}
 
footer { 
    display: block;
}
.copy {
    text-align: center;
    background: #53bed6;
    padding: 1em 1em;
}
	</style>
  
</head>

<body>

  <meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
<meta http-equiv="x-ua-compatible" content="ie=edge">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.5/css/bootstrap.min.css" integrity="sha384-AysaV+vQoT3kOAXZkl02PThvDr8HYKPZhNT5h/CXfBThSRXQ6jW5DO2ekP5ViFdi" crossorigin="anonymous">
<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css" rel="stylesheet" media="screen" >
<meta name="keywords" content="Web Developer, CSS, HTML, Bootstrap, jQuery, JavaScript, Germany, IT" />
<link href="css/style.css" rel='stylesheet' type='text/css' />
<link href=('http://getbootstrap.com/dist/css/bootstrap.css');
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  </head>
 <body>
   <div class="container">
	<!--nav starts here-->
 	<div class="topnav" id="myTopnav">
		<a href="#home">Home</a>
		<a href="#about">About</a>
		<a href="#projects">Projects</a>
		<a href="https://wendopen.wordpress.com/" data-hover="My Blog" target="_blank">My Blog</a>
		<a href="javascript:void(0);" class="icon" onclick="myFunction()">&#9776;</a>
	</div>
	<!--nav ends here-->
	
	<!--social links starts here-->
		<div class="banner" id="home"><!--banner div with id:"home" starts here-->
			<div class="intro-header">
        <!--intro-header-->
        
			 	<div class="intro-message">
				  <h1>Joyce Wendo</h1>
				  <a href="index.html">
			<h3><strong>Frontend Web Developer</strong>       </h3>
			</a>
			<hr class="intro-divider">
				 <ul class="list-inline intro-social-buttons">
						<li><a href="https://github.com/Jwendo" target="_blank" class="btn btn-default btn-lg"><i class="fa fa-github fa-fw"></i> <span class="network-name">Github</span></a></li>
						<li><a href="https://www.linkedin.com/in/wendo/" target="_blank" class="btn btn-default btn-lg"><i class="fa fa-linkedin fa-fw"></i> <span class="network-name">Linkedin</span></a></li>
						<li><a href="https://codepen.io/Wendo/" target="_blank"class="btn btn-default btn-lg"><i class="fa fa-codepen fa-fw"></i> <span class="network-name">Codepen</span></a>       </li>
						<li><a href="https://medium.com/@jwendo" target="_blank" class="btn btn-default btn-lg"><i class="fa fa-medium fa-fw"></i> <span class="network-name">Medium</span></a>       </li>
						<li><a href="https://stackoverflow.com/users/6299876/wendo-develops" target="_blank" class="btn btn-default btn-lg"><i class="fa fa-stack-overflow fa-fw"></i> <span class="network-name">StackOverflow</span></a>       </li>
					</ul>
				</div>
			
			</div><!--intro-header stops here-->
		</div><!--banner div ends here-->

		<!--about section text starts here-->
		<div id="about">  
			<img src="https://lh3.googleusercontent.com/8eKihvKUcjjw8gnRic6SltsEcC-30sUNvBIlPPnWie_ykNubYeP_t2kUxs3b_BQcovwNkw=s90" alt="Wendo Develops" />
			<h4><strong> I am a Frontend Web Developer  who is able to code web pages from the ground up using HTML5, CSS3, Bootstrap, jQuery, JavaScript and currently putting more focus on Angular.</strong></h4>
						  
			<p>I recently graduated from Silicon Valley's Udacity with a Data Science Nanodegree Powered by Bertelsmann. The reason I studied Data Science is because I feel data is exploding at a very high speed and there is the need to make sense of it by harnessing it towards the practical web applications that I create.</p>
						   
			<p>I am  just as enthusiastic about big data as I am about web development and my current goal is to continue building my skills in web development and data science so that I can use the vast data to develop insights that would help deliver intelligent solutions. This will enhance customer experience as well as optimize business performance. </p>

			<p>I taught IT in a few Colleges in Nairobi and  since Programming was my favorite subject, I capitalized on this, digging deep into fundamental understanding of design concepts, cross browser development  and API implementation.</p>

			<p>After almost a decade of teaching IT and moving to Germany, I have learned the German language, gone through an internship and can easily communicate with anyone and fellow developers to establish the necessary requirements to complete projects in a professional and timely manner.</p>
							
			<p>I have expertise Search Engine Optimization, Photoshop, Social Media marketing as well as technical blog writing.</p>
							
		</div>
				
		<!--Portfolio-->
		<div class="container content-portfolio" id="projects">
  			<h2>Frontend Development Projects</h2>
			<div class="row">
				<div class="col-sm-6">
					<div class="thumb">
					  <a href="https://jwendo.github.io/" target="_blank">
						<img class="img-responsive" src="https://github.com/Jwendo/shambula-music/blob/master/wendodevelops.JPG?raw=true" class="img-responsive" alt="Wendo Developer">
					</div>
					  </a>
					<div class="hover-opaque">
					</div>
					
				</div>
				<div class="col-sm-6">
					<div class="thumb">
					  <a href="http://www.wendojoy.com" target="_blank">
						<img class="img-responsive" src="IMG_20180815_052008_143.jpg?raw=true" class="img-responsive" alt="wendo-Joy">
					</div>
					  </a>
					<div class="hover-opaque">
					</div>
				</div>
			</div><!-- end of row -->
			<div class="row">
				<div class="col-sm-6">
					<div class="thumb">
					  <a href="http://www.pensbywendo.com" target="_blank">
						<img class="img-responsive" src="https://github.com/Jwendo/jwendo.github.io/blob/master/pens%20by%20wendo.PNG?raw=true" class="img-responsive" alt="Myblog">
              				</div>
					  </a>
					<div class="hover-opaque">
					</div>
				</div>
				<div class="col-sm-6">
					<div class="thumb">
					  <div class="thumb">
					  <a href="https://wendopen.wordpress.com/" target="_blank">
						<img class="img-responsive" src="https://theme-fusion.com/wp-content/uploads/2015/03/How-to-Create-a-WordPress-Post.png" class="img-responsive" alt="Myblog">
              				</div>
				</div>
			</div><!-- end of row -->
			<h2>Backend Development Projects</h2>
			<div class="row">
				<div class="col-sm-6 hover-opaque">
					<div class="thumb">
					  <a href="" target="_blank">
						<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTrrYVIxS-mMqnUSH6f2L4vWUBjGmBEQDDWyWujdbK_m48W--4s" class="img-responsive" alt="Coming Soon">
					</div>
					  </a>
					</div>
				</div>
				
				<div class="col-sm-6 hover-opaque">
					<div class="thumb">
					  <a href="" target="_blank">
						<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTrrYVIxS-mMqnUSH6f2L4vWUBjGmBEQDDWyWujdbK_m48W--4s" class="img-responsive" alt="Coming Soon">
						</div>
					  </a>
					</div>
				</div>
			</div>
		</div>
		
		
		
  <!--footer-->
<footer class="copy">
    

        <p>&copy; 2019 All Rights Reserved </p>
		
		
		<!--back to top button-->
		<button onclick="topFunction()" id="myBtn" title="Go to top"><strong>TOP</strong></button>

   
</footer>
  <script src='https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js'></script>
<script src='https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.0.0-alpha.6/js/bootstrap.min.js'></script>
<script src='https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/js/bootstrap.min.js'></script>

  

    <script  src="js/index.js">
	    //JS code for responsive navigation bar
	function myFunction() {
  	  var x = document.getElementById("myTopnav");
  		  if (x.className === "topnav") {
       			 x.className += " responsive";
   		 } else {
    	    x.className = "topnav";
   	 }
	}
//Show the scroll to top button when the user scrolls down to 100px
	window.onscroll = function() {scrollFunction()};
	function scrollFunction() {
 	   if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
       		 document.getElementById("myBtn").style.display = "block";
  	  } else {
       	 document.getElementById("myBtn").style.display = "none";
   	 }
	}
//When the user clicks on the "top" button, scroll to the top of the document
	function topFunction() {
   	 document.body.scrollTop = 0;
   	 document.documentElement.scrollTop = 0;
	}
	   </script>




</body>

</html>

You can use the [editor on GitHub](https://github.com/Jwendo/portfolio/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Jwendo/portfolio/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

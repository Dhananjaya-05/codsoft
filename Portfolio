#html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
	<meta charset="utf-8" />
	<meta http-equiv="X-UA-Compatiable" content="IE=edge" />
	<meta name="viewport" content="width=device=width, initial-scale.0" />
	<title>My Portfolio Page</title>
	<link rel="stylesheet" href="style.css" />
	<script src="http://kit.fontawesome.com/1d53a989c7.js" crossorigin="anonymous"></script>
</head>
<body>
	<div id="header">
		<div class="container">
			<nav>
				<img src="img/black.png.jpg" />
				<ul>
					<li><a href="#header">Home</a></li>
					<li><a href="#about"></a>About</li>
					<li><a href="#portfolio"></a>Portfolio</li>
					<li><a href="#contact"></a>Contact</li>
				</ul>
			</nav>
			<div class="header-text">
				<p>Web Developer</p>
				<h1>Hello there!</h1>
				<h2>I am <span>Dhananjaya Nayak</span> from<span> India</span><br /></h2>
				<h3><span>Studying B.Tech from college of Engineering Bhubaneswar</span></h3>
			</div>
		</div>
	<!-----------------ABOUT------------------->
	<div id="about">
		<div class="container">
			<div class="row">
				<div class="about-col-1">
					<img src="C:\Users\HP\OneDrive\Pictures\picture\IMG20221201201439.jpg" />
				</div>
				<div class="about-col-2">
					<h1 class="sub-title">About Me</h1>
					<p><br />ABOUT<br /><br />A Fulltime learner who is keen to find and challenging opportunities to grow.Looking for    		            		enriching exposure oriented opportunities to addd values in line with acheiving the goals.</p>
					<h2 class="s-title"><br />skills</h2>
					
					<div class="tab-contents active-tab" id="skills">
						<u1>
							<li><span>c++,java</span><br />To make Management system</li>
							<li><span>Web Developer</span><br />Web app interface</li>
						</ul>
					</div>
					
					<h2 class="s-title"><br />Experience</h2>
					<div class="tab-contents active-tab" id="experience">
					<ul>
						<li><span>2023</span><br />online webinar on cloud computing<br /></li>
						</ul>
					</div>
					
					<h2 class="s-title"><br />Education</h2>
					<div class="tab-contents active-tab" id="education">
						<ul>
							<li><span>2019</span><br />P.N.H.S-CHSE</li>
							<li><span>2019-2021</span><br />B.H.S.S-CHSE</li>
							<li><span>2021-2025</span><br />COEB-B.TECH(CSE)</li>
						</ul>
					</div>
				</div>
			</div>
		</div>
	</div>
	<!--------------------PORTFOLIO------------------------>
	<div id="portfolio">
		<div class="container">
			<h1 class="sub-title">My Work</h1>
			<div class="work-list">
				<div class="work">
				 	<img src="https://media.istockphoto.com/id/1168365129/photo/authentication-by-facial-recognition-concept-biometric-security-system.jpg?s=170667a&w=is&k=20&c=Pl5qoMoMJ7GRecAUpcmfPArJrcntfaccwYRgK8pkQRA=" />
					<div class="layer">
						<h3>Face Recognisation system</h3>
						<p>Deep Learning based large scale face recognisation and verification system.</p>
						<a href="#"><i class="fas fa-external-link-alt"></i></a>
					</div>
				</div>
			</div>
			<a href="#" class="btn">See more</a>
		</div>
	</div>
	<!------------ --CONTACT------------ --->
	<div id="contact">
		<div class="container">
			<div class="row">
				<div class="contact-left">
					<h1 class="sub-title">Contact me</h1>
					<p><i class="fa-solid fa-envelope"></i>Dhananjayanayak2004@gmail.com</p>
					<p><i class="fa-solid fa-phone"></i>7848091838</p>
					<div class="social-icons">
						<p><i class="fa-brands fa-linkedin"></i>DHANANJAYANAYAK</p>
					</div>
					<a href="img/Dhananjaya_Nayak_Resume.pdf" download class="btn btn2">Download Resume</a>
				</div>
			</div>
		</div>
		<div class="copyright">
			<p>0 copyrights@2023 All rights reserved.Made by Dhananjaya Nayak</p>
		</div>
	</div>
	
	<script>
		var tablinks= document.getElementsByClassName("tab-links");
		var tabcontacts= documents.getElementsByClassName("tab-contents");
		
	function opentab(tabname){
		for(tablink of tablinks){
			tablink.classList.remove("active-link");
		}
		for(tabcontent of tabcontents){
			tabcontent.classList.remove("active-tab");
		}
		event.currentTarget.classList.add("active-link");
		document.getElementById(tabname).classList.add("active-tab");
	}
	</script>
</body>
</html>

#css
*{
	margin: 0;
	padding: 0;
	font-family:'poppins',sans-serif;
	box-sizing: border-box;
}
html{
	scroll-behaviour: smooth;
}
body{
	background: black;
	color: white;
}
#header{
	width: 100%;
	height: 100vh;
	background-image: url(img/black.png.jpg);
	background-size:contain;
	background-position: center;
}
.container{
	padding: 10px 2%;
}
nav{
	display: flex;
	align-items: center;
	justify-content: space-between;
	flex-wrap: wrap;
}
.logo{
	width: 140px;
}
nav ul li{
	display: inline-block;
	list-style: none;
	margin: 10px 20px;
}
nav ul li a{
	color:#00FFFF;
	text-decoration: none;
	font-size:20px;
	position: relative;
}
nav ul li a::after{
	content: '';
	width: 0;
	height: 3px;
	background: rgb(61, 6, 163);
	position: absolute;
	left: 0;
	bottom: -6px;
	transition: 0.5s;
}
nav ul li a:hover::after{
	width: 100%;
}
.header-text{
	margin-top: 5%;
	font-size: 30px;
}
.header-text h1{
	font-size: 60px;
	margin-top: 20px;
}
.header-text h2{
	font-size: 40px;
	margin-top: 20px;
}
.header-text h2 span{
	color:#0000FF rgb(79, 17, 194);
}
.header-text h3{
	font-size: 40px;
	margin-top: 20px;
}
.header-text h3 span{
	color:#FFFFFF;
	font-size: 30px;
	font-weight: normal;
}
/*------------------ABOUT----------------*/
#about{
	padding: 80px 50px;
	color:#99FF00;
	font-size: large;
}
.row{
	display: flex;
	justify-content: space-between;
	flex-wrap: wrap;
}
.about-col-1{
	flex-basis: 35%;
}
.about-col-1 img{
	width: 100%;
	border-radius: 15px;
}
.about-col-2{
	flex-basis: 60%;
}
.sub-title{
	font-size: 60px;
	font-weight: 600;
	color:#FFFFFF;
}
.tab-titles{
	display: flex;
	margin: 20px 0 40px;
}
.tab-links{
	margin-right: 50px;
	font-size: 18px;
	font-weight: 500;
	cursor: relative;
}
.tab-links::after{
	content: '';
	width: 0;
	height: 3px;
	background: hsl(214, 100%, 50%);
	position: absolute;
	left: 0;
	bottom: -8px;
	transition: 0.5s;
}
.tab-links.active-link::after{
	width: 50%;
}
.tab-contents ul li{
	list-style: none;
	margin: 10px 0;
}
.tab-contents ul li span{
	color:#9900CC;
	font-size: 14px;
}
.tab-contents{
	display: none;
}
.tab-contents.active-tab{
	display: block;
}
/*-------------------PORTFOLIO--------------------*/
#portfolio{
	padding: 50px -8px;
}
.work-list{
	display: grid;
	grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
	grid-gap: 40px;
	margin-top: 50px;
}
.work{
	border-radius: 10px;
	position: relative;
	overflow: hidden;
}
.work img{
	width: 100%;
	border-radius: 10px;
	display: block;
	transition: transform 0.5s;
}
.layer{
	width: 100%;
	height: 0;
	background: linear-gradient(rgba(0,0,0,0.6),#3d0991);
	border-radius: 10px;
	position: absolute;
	left: 0;
	bottom: 0;
	overflow: hidden;
	display: flex;
	align-items: center;
	justify-content: center;
	flex-direction: column;
	padding: 0 40px;
	text-align: center;
	font-size: 14px;
	transition: height 0.5s;
}
.layer h3{
	font-weight: 500;
	margin-bottom: 20px;
}
.layer a{
	margin-top: 20px;
	color:#FF00FF;
	text-decoration: none;
	font-size: 25px;
	line-height: 60px;
	background: #FFFFFF;
	width: 60px;
	height: 60px;
	border-radius: 50%;
	text-align:center;
}
.work:hover img{
	transform: scale(1.1);
}
.work:hover .layer{
	height: 100%;
}
.btn{
	display: block;
	margin: 50px auto;
	width: fit-content;
	border: 1px solid #FF0000;
	padding: 14px 50px;
	border-radius: 6px;
	text-decoration: none;
	color:#FFFFFF;
	transition: "background 0.3s";
}
.btn:hover{
	background:#FF0000;
}
/*-------------------------------CONTACT-------------------------------*/
.contact-left{
	flex-basis: 35%;
	padding: 40px;
}
.contact-left p{
	margin-top: 20px;
}
.contact-left p i{
	color:#FF0000;
	margin-right: 15px;
	font-size: 25px;
}
.social-icons{
	margin-top: 30px;
}
.social-icons a{
	text-decoration: none;
	font-size: 30px;
	margin-right: 15px;
	color:#3399FF;
	display: inline-block;
	transition: transform 0.5s;
}
.social-icons a:hover{
	color:#FF0000;
	transform: translateY(-5px);
}
.btn.btn2{
	display: inline-block;
	background:#FF0000;
}
.copyright{
	width: 100%;
	text-align: center;
	padding: 25px 0;
	background:#0000FF;
	font-weight: 300;
	margin-top: 20px;
}

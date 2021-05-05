<!doctype html>
<html>
<head>
<style>
/* main  starts */
body{
	background-image: linear-gradient(62deg, #8EC5FC 0%, #E0C3FC 100%);
	font-family: "sans-serif";
	font-family: Calibri;
}

.cvWhole{
	width: 80%;
	min-height: 1000px;
	background-color: #FFFFFF;
	margin: 10px auto;
	text-align: center;
	padding-bottom: 40px;
}

.header{
	height: 100px;
	width: 100%;
}

.header .pr{
	height: 70px;
	width: 70px;
	border: 1px solid black;
	color: white;
	margin: 15px 15px;
	background: black;
	text-align: center;
	float: left
}

.header .pr p{
	font-weight: 700;
	font-size: 30px; 
	box-sizing: border-box;
	margin-bottom: 30px;
}

.menu{
	list-style: none;
	float: right;
	margin-right: 10px;
	margin-top: 30px;
}

.menu li{
	float: left;
	margin: 10px
}

h1{
	font-size: 80px;
	color: rgba(98,1,67,1.00);
}

.starter{
	border: 1px solid rgb(240, 238, 238);
	height: 150px;
	width: 80%;
	box-shadow: 10px 10px 8px 10px #C0C0C0;
	margin: 10px auto;
	display: flex;
}

.starterone{
	flex: 6;
	border: 1px solid rgb(238, 226, 226);
	text-align: left;
	padding-left: 20px;
}
/* 1 page*/
.startertwo{
	flex: 4;
	border: 1px solid rgb(238, 236, 236);
}
/* 2 page*/
.team{
	border: 1px solid rgb(250, 247, 247);
	height: 350px;
	width: 80%;
	box-shadow: 10px 10px 8px 10px #C0C0C0;
	margin: 40px auto;
}

.teaminner{
	display: flex;
	border: 1px solid rgb(238, 232, 232);
}

.teamone{
	flex: 5;
	border: 1px solid rgb(248, 248, 248);
}

.teamtwo{
	flex: 5;
}

.team ul{
	float: left;
	margin: 20px;
}

.team ul li{
	margin: 10px;
	color: #444;
}

/* 3 page*/
.enterprise{
	border: 1px solid rgb(245, 239, 239);
	height: 150px;
	width: 80%;
	box-shadow: 10px 10px 8px 10px #C0C0C0;
	margin: 10px auto;
	display: flex;
}
</style>
</head>
<!---style and head end-->
<body>
	<!----body start-->
	<div class="cvWhole">
		<!---------------------main---------------------->
		<div class="header">
			<div class="pr">
				<p>PR</p>
			</div>
			<ul class="menu">
				<li>Home</li>
				<li>About us</li>
				<li>Pricing</li>
				<li>Resources</li>
				<li>sign in</li>
			</ul>
		</div>
		
		<h1>You get more then what you pay for :)</h1>
		
		<div class="starter">
			<div class="starterone">
				<h2>Starter <i class="fa fa-chevron-down"></i></h2>
				<p>for presonal use that need advance reporting and sharing.</p>
			</div>
			<div class="startertwo">
				<h2>29$</h2>
				<p class="button">start free Trial</p>
			</div>
		</div>
		
		<div class="team">
			<div class = "teaminner"> 
				<div class="teamone">
					<h2>Team <i class="fa fa-chevron-up"></i></h2>
					<p>for Teams that need advance reporting and sharing.</p>
				</div>
				<div class="teamtwo">
					<h2>80$</h2>
					<p class="button">start free Trial</p>
				</div>
			</div>
			<ul>
				<li>This is some text</li>
				<li>This is some text</li>
				<li>This is some text</li>
				<li>This is some text</li>
				<li>This is some text</li>
				<li>This is some text</li>
				<li>This is some text</li>
			</ul>
		</div>
		
		<div class="enterprise">
			<div class="starterone">
				<h2>Enterprise <i class="fa fa-chevron-down"></i></h2>
				<p>for presonal use that need advance reporting and sharing.</p>
			</div>
			<div class="startertwo">
				<h2>29$</h2>
				<p class="button">start free Trial</p>
			</div>
		</div>
        <p> <br></p>
        <p> <br></p>
        <p> <br></p>
		<img src="de.jpg">
		<h3>Build.Review.Ship.</h3>
		<p>DownloadNow     License </p>
		<p>About Feature  Pricing  Career Help  Privacy Policy</p>
		<p>@2020 Prodify. All rights reserved </p>
		<!---------------------main---------------------->
		
	</div>
</body>
<!---------------------body---------------------->
</html>


# module2sol
Assignment
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<title>Assignment solution for module 2</title>
	<style>
		*{
			box-sizing: border-box;
			margin: 0;
			padding: 0;
		}
		h1{
			text-align: center;
			margin-top: 30px;
			margin-bottom: 80px;
			font-family: monospace;
			font-size: 50px;
		}
		#p1{
			position: relative;
			margin-top: 0px;
			margin-left: 348px;
			text-align: center;
			height: 30px;
			width: 120px;
			background-color: pink;
			border: 2px solid black;
		}
		#p2{
			position: relative;
			margin-top: 0px;
			margin-left: 348px;
			text-align: center;
			height: 30px;
			width: 120px;
			background-color: brown;
			border: 2px solid black;
		}
		#p3{
			position: relative;
			margin-top: 0px;
			margin-left: 348px;
			text-align: center;
			height: 30px;
			width: 120px;
			background-color: orange;
			border: 2px solid black;
		}
		#box {
			height: 200px;
			width: 470px;
			margin-top: 30px;
			margin-right: 20px;
			margin-left: 20px;
			margin-bottom: 10px;
			border: 2px solid black;
			text-align: ;
		}
		div {
			font-size: 20px;
			border:2px solid white;
			font-family: monospace;
			text-align: left;

		}
	.row{
		width:100%;
	}
	@media(min-width: 1200px){
		.col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7 , .col-lg-8, .col-lg-9,.col-lg-10, .col-lg-11,.col-lg-12{
			float:left;
			border: 2px solid black;
		} 
		.col-lg-1{
			width:8.33%;
		}
		.col-lg-2{
			width:16.66%;
		}
		.col-lg-3{
			width: 25%;
		}
		.col-lg-4{
			width: 33%;
		}
		.col-lg-5{
			width:41.66%;
		}
		.col-lg-6{
			width:50%;
		}
		.col-lg-7{
			width:58.33%;
		}
		.col-lg-8{
			width:66.66%;
		}
		.col-lg-9{
			width:74.99%;
		}
		.col-lg-10{
			width:83.33%;
		}
		.col-lg-11{
			width:91.66%;
		}
		.col-lg-12{
			width:100%;
		}
	}
	@media(min-width: 950px) and (max-width: 1199px){
		.col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7 , .col-md-8, .col-md-9,.col-md-10, .col-md-11,.col-md-12{
			float:left;
			border: 2px solid black;
		} 
		.col-md-1{
			width:8.33%;
		}
		.col-md-2{
			width:16.66%;
		}
		.col-md-3{
			width: 25%;
		}
		.col-md-4{
			width: 33%;
		}
		.col-md-5{
			width:41.66%;
		}
		.col-md-6{
			width:50%;
		}
		.col-md-7{
			width:58.33%;
		}
		.col-md-8{
			width:66.66%;
		}
		.col-md-9{
			width:74.99%;
		}
		.col-md-10{
			width:83.33%;
		}
		.col-md-11{
			width:91.66%;
		}
		.col-md-12{
			width:100%;
		}
	}

	</style>
</head>
<body>
	<h1> Our Menu </h1>
	<div class="row">
	<div id="box" class="col-lg-4 col-md-6" style="background-color: gray; height:200px;">
		<p id="p1">Chicken</p>
		Iorem ispum dolor sit amet, consectetur adipisicing elit, sed do eiusmod temopr incididunt ut labore et dolor magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commondo consequat.
	
	</div>
	<div id="box" class="col-lg-4 col-md-6 " style="background-color: gray; height:200px;"> <p id="p2">Beef</p>
	Iorem ispum dolor sit amet, consectetur adipisicing elit, sed do eiusmod temopr incididunt ut labore et dolor magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commondo consequat.</div>
	<div id="box" class="col-lg-4 col-md-6 " style="background-color: gray; height:200px;" > 
		<p id="p3">Sushi</p>	Iorem ispum dolor sit amet, consectetur adipisicing elit, sed do eiusmod temopr incididunt ut labore et dolor magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commondo consequat.
		
	</div>
	</div>
</body>
</html>

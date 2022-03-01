
<html >
	<head>
		<title></title>
		<style type="text/css">
		*{
			margin :0;
			padding:0;
			font-family:cursive ;
		}
		.main-manu{
			max-width:100%
			height :95vh;
		}
		.manu{
			height :25px;
			width :100%
			position :relative ;
			margin-top:50px;
		}
		.manu ul li{
			list-style-type:none;
		}
		.manu ul li a{
			font-size:15px;
			margin:9px ;
			text-decoration :none;
			text-transform:uppercase ;
			background :#333;
			color:#fff;
			font-weight:bold;
			padding:2px 2px;
			border-radius:4px;
			outline :none;
			transition :0.5s;
		}
		.manu ul li a:hover{
			color:#333;
			background :#fff;
		}

		.name {
			position :absolute ;
		    margin-top:23px;
		    margin-left:26px;
		    font-size:28;
		    color:red;
		 }
		 
	h4{
		position :absolute ;
		margin-left:6rem;
		margin-top:50px;
		font-size:23px;
		color:blue;
		}
		
		.search {
		    width :60%;
		    height :9px;
		    display :inline-block;
		    position :relative ;
		    border-radius:18px;
		}
		.search input{
		    position :absolute ;
		    top:10px;;
		    left:6rem;
		    font-family:cursive ;
		    padding :5px 20px;
		}
		::placeholder {
			font-size:16px;
		}
	.btn{   
			position :absolute  ;
			width :3rem;
			height:1rem;
			left:18rem;
			top:10px;
			border:1px solid black ;
			border-radius:4px;
			background:none;
			text-decoration :none ;
			text-align:center;
			padding :5px 6px 5px 4px;
			background :none ;
			transition :0.3s;
		}
		.btn:hover{
			color:white ;
			background :orange ;
			font-weight:bold;
			
		}
		.manu-card{
			width:250;
			height :300px;
			background :transparent ;
			border:1px solid #333;
			box-shadow:0 4px 8px 0;
			position :relative  ;
			left:-25px;
			top :55%;
			margin :auto;
			margin-top:12rem;
			margin-left:5rem;
			box-sizing:border-box;
			padding :16px;
			border-radius:20px;
			transition :0.4s;
		}
		.manu-card:hover{
			background-color:transparent ;
		}
		.manu-card h2{
			text-align:center;
			color:red;
			font-size:28px;
			
		}
		.logo{
			font-weight:bold;
			font-size:15px;
			margin:7px;
		}
		.login{
			width:200px;
			height:28px;
			border-radius:3px;
			text-align:center;
			margin-left:10px;
			justify-contact:center;
			padding :5px;
		}
		::placeholder {
			font-size:16px;
			text-align:center;
		}
		.login:hover{
			background-color:pink;
		}
		.log{
			display :block;
			text-align:center;
			margin:5px;
			font-size:18px;
			text-decoration :none;
			transition :0.2s;
		}
		.log:hover{
			color:red;
			font-size:25px;
		}
		.have{
			text-align:center;
			display :block;
			margin:5px;
			font-size:18px;
			text-decoration :none;
			transition :0.2s;
		}
		.have:hover{
			color:red;
			font-size:25px;
			background :none;
		}
		.great{
			margin-top:20px;
			margin-left:35px;
			font-size:28px;
			font-weight:bold;
		}
		.great:hover{
			width :100%;
			font-size:38px;
			text-shadow:5px ;
		}
		</style>
	</head>
	<body>
		<div class ="main-manu">
			<div class="search">
				<input type="text" name="search " placeholder ="Enter your search">
				<button><a href="#" class="btn">search</a></button>
			</div>
			<div class ="manu">
				<ul>
					<li>
						<a href="#" >home</a>
						<a href="#" >about</a>
						<a href="#" >service</a>
						<a href="#" >video</a>
						<a href="#" >vlog</a>
					</li>
				</ul>
			</div>
				<h1 class ="name">Akkas  Ali,,,</h1>
				
				<h4>If you want to be success in your life,you should must be work hard.And improved your skill.Than you will be success.</h4>
			
			<!------------------------
				login form start
			-------------------------->
			
				<div class="manu-card">
					<h2>Login Here</h2>
					<p class ="logo">Full Name:</p>
					<input type ="text" name="" placeholder ="Enter your name" class ="login">
					<p class ="logo">Email:</p>
					<input type ="email " name="email " id="email" placeholder ="Email id" class ="login" required >
					<p class ="logo" for="password ">password :</p>
					<input type="Password " name="password " id="password" placeholder ="Password " class ="login">
					<a href="#"class="log">login</a>
					<a href="#" class="have">Create an new account</a>
				</div>
				
				<div class ="great">Thanks for watching.... </div>
		</div>
	</body>
</html>

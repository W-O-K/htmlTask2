
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<title>Dashboard - Piggyvest</title>
	<link rel="stylesheet" href="">

	<style type="text/css" media="screen">
		*{
			font-family: Arial, helvatica, sans-serif;
		}
	body{
		background-color: #ADD8E6;
	}
	.form{
		overflow: hidden;
		margin: auto;
		width: 30%;
		height: 100%;
		padding: 30px 30px 100px 30px;
		border-style: solid ;
		border-width: ;
		border-color: white; 
		border-radius:30px 30px 30px 0px;
		background-color: white;
		}

	label{
		color: #47476b;
		font-size: 12px;
		font-weight: 550;
	}

	input {
		font-size: 15px;
	}

	.top{
		margin-bottom: 35px;
	}

	h1{
		color:#00008B;
		text-align: center;
		margin: 0;
		font-size: 18px;
	}
	
	div a {
    text-align: center;
    display: block;
    margin: 0 auto;
	}
	
	p{
		text-align: center;	
		color: #a2a2c3;
		margin-top: 0;

	}
	input, select {
		margin: 10px 0 25px;
		width: 100%;
		padding: 10px 0px 10px 10px;
		border: none;
		border-radius: 4px;
		background-color: #efeff5;
	}
input[type=submit] {
  width: 100%;
  background-color: #0000b3;
  color: white;
  padding: 15px 20px;
  margin: 1px 0;
  border: none;
  border-radius:9px 9px 9px 0px; ;
  cursor: pointer;
  font-weight: 600;
	}
input[type=submit]:hover {
    background-color: #000066;
  }
  select{
  	color: #47476b;
  }

.logo {
	height: 61px;
	width: 191.5px;
	}

.login{
	margin-top: 30px;
	margin-bottom: 30px;
}

.link{
	text-decoration: none;
	color: white;
	font-size: 12px;
	font-weight: 550;
}

.link:hover{
	color: #47476b;
}


</style>
</head>
<body>
	<header id="header" class="">
		<!-- logo should be a link too -->
		<div class="box" >
			<a href=""><img class="logo"  src="https://res.cloudinary.com/wok/image/upload/v1585784418/piggy-png_1__psopv5.png" alt="piggyvest logo"></a>
		</div>
		
	</header><!-- /header -->
	<div class="form">
		<div class="top">
			<h1>Create a Secure Account</h1>
			<p>Welcome to the future of Savings & Investment</p>
		</div>
		<form action="piggyvest_submit" method="get" accept-charset="utf-8">
			<label for="fname">Full Name</label><br>
			<input type="text" id="fname" name="" placeholder="Full Name"><br>
			<label for="mail">Email Address</label><br>
			<input type="text" id="mail" name="" placeholder="Email Address"><br>
			<label for="number">Phone Number</label><br>
			<input type="text" id="number" name="" placeholder="Phone Number"><br>
			<label for="password">Password</label><br>
			<input type="text" id="password" name="" placeholder="Password"><br>
			<label for="promo">Referrer Phone or Promo Code(Optional)</label><br>
			<input type="text" id="promo" name="" placeholder="Referrer Phone or Code"><br>
			<label for="howDidYouHear">How Did You Hear About Us? (Optional)</label><br>
			<select id="howDidYouHear" name="" >
    <option value="default">Click to select</option>
    <option value="facebook">Facebook</option>
    <option value="twitter">Twitter</option>
    <option value="instgram">Instagram</option>
    <option value="friends">Firend/Family/Coworker/Referral</option>
    <option value="google">Google search</option>
    <option value="playstore">Google playstore</option>
    <option value="instgram">Online Blog</option>
    <option value="instgram">Local Newspaper</option>
  </select><br>
  <input type="submit" value="CREATE ACCOUNT">
  		</form>
	</div>
	<div class="login">
	<a class="link" href="">Already have an account? Log In</a>	
	</div>
	
	
</body>
</html>


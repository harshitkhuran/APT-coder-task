<template>
	<footer>
	  <p>
		<a href="https://www.facebook.com/harshit.khurana.75098?mibextid=ZbWKwL" class="fa fa-facebook">Facebook</a>
		<a href="https://wa.me/qr/II6OH35PIWRZJ1" class="fa fa-whatsapp">Whatsapp</a>
		<a href="https://instagram.com/harshit2172?igshid=OGQ5ZDc2ODk2ZA==" class="fa fa-instagram">Instagram</a>
	  </p>
  
	  <br>
  
	  <div class="container">
		<div class="row">
		  <div class="col-md-12 col-sm-12">
			<div style="color:#ffffff;" class="wow fadeInUp footer-copyright">
			  <p>Made in India <br> BY Harshit Khurana </p>
			</div>
		  </div>
		</div>
	  </div>
	</footer>
  </template>
  
  <script>
  export default {
	name: 'Footer', // If this component is meant to be globally registered, you can remove this line
	// Any additional logic or properties can be added here
  }
  </script>
  
  <style scoped>
  footer {
	padding: 0px 0px 0px 0px;
	background-color: black;
	margin: 0px;
  }
  
  .fa {
	padding: 20px;
	font-size: 23px;
	width: 60px;
	text-align: center;
	text-decoration: none;
	margin: 5px 2px;
	border-radius: 50%;
  }
  
  .fa:hover {
	opacity: 0.5;
	text-decoration: none;
  }
  
  .fa-facebook {
	background: #3B5998;
	color: white;
	margin-top: 30px;
  }
  
  .fa-whatsapp {
	background: #25d366;
	color: white;
  }
  
  .fa-twitter {
	background: #55ACEE;
	color: white;
  }
  
  .fa-instagram {
	background: #125688;
	color: white;
  }
  
  p {
	text-align: center;
	font-size: 23px;
  }
  </style>
  
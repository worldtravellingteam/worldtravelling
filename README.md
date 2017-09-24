<html>
<head>
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"><!--Bootstrap library--------------->
<link href="css/bootstrap.min.css" rel="stylesheet">
<style>
nav ul li
{
	font-family:open-sans;
	font-size:18px;
	font-weight:bold;
}

.hero
{
background-repeat:no-repeat;
background-image:url("hotel3.jpg");
opacity:0.95;
background-size:cover;
alt:asda;
padding:0 !important;
z-index:1;
background-position: 100% 100%;
}
.container-fluid
{
	padding:0 !important;
	margin:auto !important;
}
.navbar
{
    box-shadow:3px 2px 3px grey;

background-color:white;
z-index:1000;
width:100%;
border-radius:0px;
}
input[type="text"]
{
	font-size:24px;
}
input[type="text"] placeholder
{
padding:55px;
}
#b1
{
border-radius:0;
width:60;
height:40px;
margin-left:20;
padding:5px;
font-weight:bold;
font-size:20px;
margin-top:15px;
}
footer ul li
{
padding-top:10;
}
input[type="radio"] checked
{
color:red;
}

</style>

</head>
<body>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<script src="js/bootstrap.min.js"></script>
<header>
<div class="container-fluid" style="padding:0;margin:auto">
<nav class="navbar navbar-default navbar-fixed-top">
<div class="container-fluid">
<div class="row" style="padding:2">
<div class="logo col-md-2" style="margin-left:60px;margin-top:-15px !important;">
<a class="navbar-brand" href="#"><img src="worldtravel1.png" width="85px" height="65px"></a>
</div>
<div class="col-md-6 navbar-text" style="margin-top:23px;border-right:0.1px solid lightgrey">
<ul class="nav navbar-nav list-inline text-primary">
<li>
Hotels</li><li style="opacity:0.5;color:lightgrey">|</li>
<li style="padding-left:5px">
Holiday Homes
</li><li style="opacity:0.5;color:lightgrey">|</li>
<li style="padding-left:5px">
Restaurent
</li><li style="opacity:0.5;color:lightgrey">|</li>
<li style="padding-left:5px">
Things to do
</li><li style="opacity:0.5;color:lightgrey">|</li>
<li style="padding-left:5px">
Flights
</li>
<li>
</li>
</ul>
</div>
<div class="col-md-3 navbar-content" style="">
<ul class="nav navbar-nav list-inline" style="">
<li><i class="fa fa-home" style="font-size:25px;margin-top:22;padding-left:25"></i></li>
<li><button id="b1" class="btn btn-success navbar-btn text-center">JOIN</button></li>
<li><i class="fa fa-search" style="font-size:25px;margin-top:22;padding-left:15"></i></li>
</ul>
</div></div></div>
</nav>
</div>

<div class="hero" style="padding-top:0;margin-top:65px;position:relative" >
<div class="container" style="padding-top:250px">
<div class="row">
<span class="col-md-offset-2 col-md-10" style="padding-left:0;font-size:45px;color:white;font-family:Monospace">Latest Reviews.Lowest prices.</span>
</div>

<div class="row text-center" style="padding-bottom:150px"><center>
<div class="col-md-offset-1 col-md-4" style="background-color:;padding:0;margin:auto">
<div class="input-group" style="float:right;position:relative">  
	<input type="text" class="form-control" placeholder="Search" style="border-radius:100px 0px 0px 100px;height:50px;width:100%">
	</div>
	</div>
	<div class="col-md-2"  style="background-color:;padding:0;margin:auto">
	<div class="input-group" style="float:left;width:100%">
	<select class="form-control" style="width:100%;height:50px;">
	<option value="1 room,2 Guests">1 room,2 Guests</option>
	<option value="2 room,4 Guests">2 room,4 Guests</option>
	<option value="4 room,8 Guests">4 room,8 Guests</option>
	</select>
	</div>
	</div>
	<div class="col-md-2" style="background-color:;padding:0 !important;margin:auto">
	<div class="input-group" style="float:left;width:100%" >
	<input type="date" class="form-control" value="Check in-Check out" style="width:100%;height:50px;">
	</div>
	</div>
<div class="col-md-2" style="background-color:;padding:0 !important;margin:auto">
    <div class="input-group input-group-btn" >
      <button class="form-control btn btn-success" type="submit" style="border-radius:0 100px 100px 0;height:50px;float:left">
        <span style="font-size:20">Find Hotels</span>
      </button>
    </div>
	</div></center>
  </div>
  </div>
</div>


<div class="container">
<div class="row" >
<div class="col-md-7" style="padding-top:50px;font-family:Miriam">
<strong><span style="padding-top:80px;font-size:25;color:green">Save up to 30% on hotels.</span></strong>
<p><span  style="padding-top:60px;padding-right:50px;font-size:20;color:black">TripAdvisor compares prices from 200+ booking sites to help you find the lowest price on the right hotel for you.</span></p>
</div>
<div class="col-md-4" style="margin-left:40;background-color:47b447;margin-top:10px;font-family:Miriam">
<span><img src="c.png" width="150px" height="150px" style="float:left"></span>
<span style="position:absolute;top:20px;font-size:21;color:white">Fing the best values on hotels and make the most out of your trip.<p style="padding:10">See How</p></span>
</div>
</div>
<div class="top_hotels">
<div class="row" style="padding-top:50px">
<div class="col-md-5" style="padding-top:0;font-family:Miriam">
<span style="padding-top:80px;"><h3><strong>Travellers' choice : Top Hotels</strong></h3></span>
</div>
<div class="col-md-7" style="padding-top:10;font-family:Miriam">
<span style="font-size:21;float:right;color:black">See all</span>
</div>
</div>
<div class="gallery">
<div class="row">
<div class="col-md-3">
<figure><img src="hotel.jpg" width="250px" height="150px"><figcaption class="text-center text-info" style="font-size:25;font-family:open-sans">France Hotel</figcaption></figure>
</div>
<div class="col-md-3">
<figure><img src="hotel2.jpg" width="250px" height="150px"><figcaption class="text-center text-info" style="font-size:25;font-family:open-sans">France Hotel</figcaption></figure>
</div>
<div class="col-md-3">
<figure><img src="bus.jpg" width="250px" height="150px"><figcaption class="text-center text-info" style="font-size:25;font-family:open-sans">France Hotel</figcaption></figure>
</div>
<div class="col-md-3">
<figure><img src="bus1.jpg"width="250px" height="150px"><figcaption class="text-center text-info" style="font-size:25;font-family:open-sans">France Hotel</figcaption></figure>
</div>
</div>
</div>
</div>

<div class="resorts">
<div class="row" style="padding-top:50px">
<div class="col-md-5" style="padding-top:0;font-family:Miriam">
<span style="padding-top:80px;"><h3><strong>Travellers' choice : All inclusive resorts</strong></h3></span>
</div>
<div class="col-md-7" style="padding-top:10;font-family:Miriam">
<span style="font-size:21;float:right;color:black">See all</span>
</div>
</div>
<div class="gallery">
<div class="row">
<div class="col-md-3">
<figure><img src="bus2.jpg" width="250px" height="150px"><figcaption class="text-center text-info" style="font-size:25;font-family:open-sans">France Hotel</figcaption></figure>
</div>
<div class="col-md-3">
<figure><img src="busn.png" width="250px" height="150px"><figcaption class="text-center text-info" style="font-size:25;font-family:open-sans">France Hotel</figcaption></figure>
</div>
<div class="col-md-3">
<figure><img src="cs.jpg" width="250px" height="150px"><figcaption class="text-center text-info" style="font-size:25;font-family:open-sans">France Hotel</figcaption></figure>
</div>
<div class="col-md-3">
<figure><img src="hotel2.jpg"width="250px" height="150px"><figcaption class="text-center text-info" style="font-size:25;font-family:open-sans">France Hotel</figcaption></figure>
</div>
</div>
</div>
</div>

<div class="small_hotels">
<div class="row" style="padding-top:50px">
<div class="col-md-5" style="padding-top:0;font-family:Miriam">
<span style="padding-top:80px;"><h3><strong>Travellers' choice : All inclusive resorts</strong></h3></span>
</div>
<div class="col-md-7" style="padding-top:10;font-family:Miriam">
<span style="font-size:21;float:right;color:black">See all</span>
</div>
</div>
<div class="gallery">
<div class="row">
<div class="col-md-3">
<figure><img src="events.jpg" width="250px" height="150px"><figcaption class="text-center text-info" style="font-size:25;font-family:open-sans">France Hotel</figcaption></figure>
</div>
<div class="col-md-3">
<figure><img src="events1.gif" width="250px" height="150px"><figcaption class="text-center text-info" style="font-size:25;font-family:open-sans">France Hotel</figcaption></figure>
</div>
<div class="col-md-3">
<figure><img src="des.jpg" width="250px" height="150px"><figcaption class="text-center text-info" style="font-size:25;font-family:open-sans">France Hotel</figcaption></figure>
</div>
<div class="col-md-3">
<figure><img src="hotel2.jpg"width="250px" height="150px"><figcaption class="text-center text-info" style="font-size:25;font-family:open-sans">France Hotel</figcaption></figure>
</div>
</div>
</div>
</div>

<div class="top_destination">
<div class="row" style="padding-top:50px">
<div class="col-md-5" style="padding-top:0;font-family:Miriam">
<span style="padding-top:80px;"><h3><strong>Travellers' choice : All inclusive resorts</strong></h3></span>
</div>
<div class="col-md-7" style="padding-top:10;font-family:Miriam">
<span style="font-size:21;float:right;color:black">See all</span>
</div>
</div>
<div class="gallery">
<div class="row">
<div class="col-md-3">
<figure><img src="lab2.jpg" width="250px" height="150px"><figcaption class="text-center text-info" style="font-size:25;font-family:open-sans">France Hotel</figcaption></figure>
</div>
<div class="col-md-3">
<figure><img src="lab3.jpg" width="250px" height="150px"><figcaption class="text-center text-info" style="font-size:25;font-family:open-sans">France Hotel</figcaption></figure>
</div>
<div class="col-md-3">
<figure><img src="lab4.png" width="250px" height="150px"><figcaption class="text-center text-info" style="font-size:25;font-family:open-sans">France Hotel</figcaption></figure>
</div>
<div class="col-md-3">
<figure><img src="lab6.jpg"width="250px" height="150px"><figcaption class="text-center text-info" style="font-size:25;font-family:open-sans">France Hotel</figcaption></figure>
</div>
</div>
</div>
</div>

<div class="popular_destination">
<div class="row" style="padding-top:50px">
<div class="col-md-8" style="padding-top:0;font-family:Miriam">
<span style="padding-top:80px;"><h3><strong>Travellers' choice : Hotels in Popular destinations</strong></h3></span>
</div>
</div>
<div class="info" style="font-family:rockwell">
<div class="row">
<div class="col-md-12">
<p>Shopping for hotels.You are at the right place.With millions of reviews from travellers worldwide , we can help you to find hotel,inn or bed & breakfast.And when you are ready to book , we check 200+ sites to find you the highest and lowest hotel prices.It's all right here on TripAdvisor.</p>
</div>
</div>
</div>
</div>

<div class="ct">
<div class="row" style="padding-top:20px">
<div class="col-md-8" style="padding-top:0;font-family:arial">
<span style="padding-top:80px;"><h5><strong>Top Indian states & cities</strong></h5></span>
</div>
</div>
<div class="row">
<ul class="col-md-4" style="list-style-type:none;font-size:15px">
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
</ul>
<ul class="col-md-4" style="list-style-type:none;font-size:15px">
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
</ul>
<ul class="col-md-4" style="list-style-type:none;font-size:15px">
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
<li>Ahmedabad</li>
<li>Patna</li>
</ul>
</div>
</div>
</div>
<footer class="footer" style="background-color:lightgrey;padding-bottom:20">
<div class="container text-center" style="padding-top:25">
<div class="row">
<div class="col-md-8" style="padding:15;padding-right:0">
<ul class="col-md-3" style="list-style-type:none;">
<h5><strong>About Advisory</strong></h5>
<li>About us</li>
<li>Press</li>
<li>Content Integrity</li>
</ul>
<ul class="col-md-2" style="list-style-type:none">
<h5><strong>Explore</strong></h5>
<li>Write a review</li>
<li>Join</li>
<li>Green leaders</li>
<li>Help center</li>
</ul>
<ul class="col-md-3" style="list-style-type:none">
<h5><strong>Currency/Country</strong></h5>
<select class="form-control"><li><option value="INR"> &#8377; INR</option></li>
<li><option value="NC">Nepali</option></li>
</select>
<select class="form-control" style="margin-top:15"><li><option value="INR"> INDIA</option></li>
<li><option value="NC">Nepal</option></li>
</select>
</ul>
</div>
</div>
<div class="row">
<div class="col-md-8" style="padding:15;padding-right:0">
<ul class="col-md-3" style="list-style-type:none;">
<h5><strong>Do business with us</strong></h5>
<li>Owners & DMO/CVB</li>
<li>Business advantage</li>
</ul>
<ul class="col-md-2" style="list-style-type:none;">
<h5><strong>Get the App</strong></h5>
<li>Iphone App</li>
<li>Android App</li>
</ul>
<ul class="col-md-3" style="list-style-type:none;">
<h5><strong>Follow us</strong></h5>
<li>Facebook</li>
<li>Twitter</li>
<li>Pintrest</li>
<li>Instagram</li>
</ul>

</div>
</div>
<div class="footer-content" style="padding-top:20">
<div class="row">
<img src="worldtravel1.png" style="float:left;width:110px;height:100px">
<span style="float:left;padding-left:155px;margin-top:35px;font-size:20">Know better <input type="radio" checked> Book better <input type="radio" checked> Go better</span>
</div></div>
<hr>
<span style="font-size:20;font-family:sans-seriff">Copyright &copy; 2017 Developing Webs</span> </div>
</footer>
</header>
</body>
</html>

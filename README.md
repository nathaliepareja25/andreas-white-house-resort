change the text  "Your Tropical Relaxing Beach Haven in Samal"

heres the code
# andreas-white-house-resort
Website of the Resort
```html id="andreas-white-house-resort-final"
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>ANDREAS WHITE HOUSE BEACH RESORT</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family:'Poppins',sans-serif;
    background:#f5f7fa;
    color:#222;
}

header{
    height:100vh;
    background:
    linear-gradient(rgba(0,0,0,0.45), rgba(0,0,0,0.45)),
    url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e') center/cover no-repeat;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;
    padding:20px;
}

.hero h1{
    font-size:60px;
    margin-bottom:15px;
}

.hero p{
    font-size:20px;
    margin-bottom:25px;
}

.hero a{
    text-decoration:none;
    background:white;
    color:#111;
    padding:14px 28px;
    border-radius:30px;
    font-weight:600;
}

nav{
    position:sticky;
    top:0;
    z-index:1000;
    background:#111;
    padding:15px;
    text-align:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
    font-weight:500;
}

section{
    padding:70px 8%;
}

.section-title{
    text-align:center;
    margin-bottom:50px;
}

.section-title h2{
    font-size:38px;
    color:#111;
}

.section-title p{
    color:#666;
}

.rooms{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(320px,1fr));
    gap:25px;
}

.room-card{
    background:white;
    border-radius:18px;
    overflow:hidden;
    box-shadow:0 8px 20px rgba(0,0,0,0.1);
    transition:0.3s;
}

.room-card:hover{
    transform:translateY(-5px);
}

.room-card img{
    width:100%;
    height:220px;
    object-fit:cover;
}

.room-content{
    padding:22px;
}

.room-content h3{
    margin-bottom:10px;
}

.price{
    color:#0077ff;
    font-size:22px;
    font-weight:700;
    margin-bottom:15px;
}

.room-content ul{
    padding-left:18px;
    margin-bottom:20px;
}

.room-content li{
    margin-bottom:8px;
}

.book-btn{
    display:inline-block;
    background:#0077ff;
    color:white;
    padding:12px 20px;
    border-radius:10px;
    text-decoration:none;
    font-weight:600;
}

.about{
    text-align:center;
    max-width:900px;
    margin:auto;
    line-height:1.8;
}

.booking{
    background:white;
    border-radius:20px;
    padding:40px;
    max-width:700px;
    margin:auto;
    box-shadow:0 10px 20px rgba(0,0,0,0.1);
}

.booking input,
.booking select,
.booking textarea{
    width:100%;
    padding:14px;
    margin-top:12px;
    margin-bottom:20px;
    border-radius:10px;
    border:1px solid #ccc;
    font-family:'Poppins',sans-serif;
}

.booking button{
    width:100%;
    padding:15px;
    background:#0077ff;
    border:none;
    color:white;
    font-size:16px;
    border-radius:10px;
    cursor:pointer;
}

.contact{
    text-align:center;
    line-height:2;
}

.contact a{
    text-decoration:none;
    color:#0077ff;
    font-weight:600;
}

footer{
    background:#111;
    color:white;
    text-align:center;
    padding:25px;
    margin-top:50px;
}

iframe{
    width:100%;
    border:none;
    border-radius:20px;
    height:400px;
}

@media(max-width:768px){

.hero h1{
    font-size:38px;
}

.hero p{
    font-size:16px;
}

nav a{
    display:inline-block;
    margin:8px;
}

}

</style>
</head>

<body>

<header>
    <div class="hero">
        <h1>ANDREAS WHITE HOUSE BEACH RESORT</h1>
        <p>Your Tropical Relaxing Beach Haven in Samal </p>
        <a href="#rooms">Explore Rooms</a>
    </div>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#rooms">Rooms</a>
    <a href="#booking">Booking</a>
    <a href="#location">Location</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <div class="section-title">
        <h2>About Us</h2>
        <p>Your perfect beach getaway destination</p>
    </div>

    <div class="about">
        <p>
            Welcome to Andreas White House Beach Resort —
            a relaxing paradise perfect for family vacations,
            barkada outings, staycations, and unforgettable beach moments.
            Experience comfort, nature, and peaceful ocean vibes all in one place.
        </p>
    </div>
</section>

<section id="rooms">

<div class="section-title">
    <h2>Rooms & Accommodation</h2>
    <p>Comfortable stays for every guest</p>
</div>

<div class="rooms">

<div class="room-card">
<img src="https://images.unsplash.com/photo-1505693416388-ac5ce068fe85">
<div class="room-content">
<h3>Acree Woods (Standard Room)</h3>
<div class="price">₱3,000 - ₱4,000</div>
<ul>
<li>2-3 Pax</li>
<li>Bunk Bed Setup</li>
<li>TV w/ Cable</li>
<li>T&B</li>
<li>Breakfast Option Available</li>
</ul>
<a class="book-btn" href="#booking">Book Now</a>
</div>
</div>

<div class="room-card">
<img src="https://images.unsplash.com/photo-1566073771259-6a8506099945">
<div class="room-content">
<h3>Cabana Suites</h3>
<div class="price">₱7,000 - ₱7,500</div>
<ul>
<li>Upper & Lower Suites</li>
<li>1 Matrimonial Bed</li>
<li>1 Sofa Bed</li>
<li>Bathtub</li>
<li>Free 1 Hour Gym Use</li>
</ul>
<a class="book-btn" href="#booking">Book Now</a>
</div>
</div>

<div class="room-card">
<img src="https://images.unsplash.com/photo-1522708323590-d24dbb6b0267">
<div class="room-content">
<h3>Tree House 1</h3>
<div class="price">₱5,000</div>
<ul>
<li>2 Pax</li>
<li>Double Bed</li>
<li>Air-conditioned</li>
<li>Hot & Cold Shower</li>
<li>Toiletries Included</li>
</ul>
<a class="book-btn" href="#booking">Book Now</a>
</div>
</div>

<div class="room-card">
<img src="https://images.unsplash.com/photo-1505693416388-ac5ce068fe85">
<div class="room-content">
<h3>Tree House 2</h3>
<div class="price">₱6,500</div>
<ul>
<li>3-4 Pax</li>
<li>Double Bed + Single Bed</li>
<li>Air-conditioned</li>
<li>TV w/ Cable</li>
<li>Hot & Cold Shower</li>
</ul>
<a class="book-btn" href="#booking">Book Now</a>
</div>
</div>

<div class="room-card">
<img src="https://images.unsplash.com/photo-1505693416388-ac5ce068fe85">
<div class="room-content">
<h3>Family Room</h3>
<div class="price">₱20,500</div>
<ul>
<li>16-18 Pax</li>
<li>2 Shower Rooms</li>
<li>Hot & Cold Shower</li>
<li>Personal Refrigerator</li>
<li>Breakfast Included</li>
</ul>
<a class="book-btn" href="#booking">Book Now</a>
</div>
</div>

<div class="room-card">
<img src="https://images.unsplash.com/photo-1522798514-97ceb8c4f1c8">
<div class="room-content">
<h3>Barkadahan Room</h3>
<div class="price">₱12,000</div>
<ul>
<li>10-12 Pax</li>
<li>Air-conditioned</li>
<li>Carpeted Room</li>
<li>2 Shower Rooms / Toilet</li>
<li>TV w/ Cable</li>
</ul>
<a class="book-btn" href="#booking">Book Now</a>
</div>
</div>

<div class="room-card">
<img src="https://images.unsplash.com/photo-1505693416388-ac5ce068fe85">
<div class="room-content">
<h3>Atelier Room</h3>
<div class="price">₱10,000</div>
<ul>
<li>Good for 6 Pax</li>
<li>TV w/ Cable</li>
<li>Personal Refrigerator</li>
<li>Toiletries Included</li>
<li>Breakfast Included</li>
</ul>
<a class="book-btn" href="#booking">Book Now</a>
</div>
</div>

</div>
</section>

<section id="booking">

<div class="section-title">
<h2>Book Your Stay</h2>
<p>Reserve your perfect vacation today</p>
</div>

<div class="booking">

<form onsubmit="sendBooking(event)">

<input type="text" placeholder="Full Name" required>

<input type="email" placeholder="Email Address" required>

<input type="tel" placeholder="Contact Number" required>

<input type="date" required>

<select required>
<option value="">Select Room</option>
<option>Acree Woods</option>
<option>Cabana Suites</option>
<option>Tree House 1</option>
<option>Tree House 2</option>
<option>Family Room</option>
<option>Barkadahan Room</option>
<option>Atelier Room</option>
</select>

<textarea rows="5" placeholder="Special Requests"></textarea>

<button type="submit">Submit Booking Request</button>

</form>

<p id="booking-message" style="margin-top:20px;font-weight:600;"></p>

</div>

</section>

<section id="location">

<div class="section-title">
<h2>Our Location</h2>
<p>Find us بسهولة</p>
</div>

<iframe
src="https://maps.google.com/maps?q=ANDREAS%20WHITE%20HOUSE%20BEACH%20RESORT&t=&z=15&ie=UTF8&iwloc=&output=embed">
</iframe>

</section>

<section id="contact">

<div class="section-title">
<h2>Contact Us</h2>
<p>We would love to hear from you</p>
</div>

<div class="contact">
<p>📞 0916-398-4410</p>

<p>
📘 Facebook:
<a href="https://facebook.com" target="_blank">
Andreas White House Beach Resort 2.0
</a>
</p>

<p>🌴 Thank you for choosing Andreas White House Beach Resort!</p>

</div>

</section>

<footer>
<p>© 2026 ANDREAS WHITE HOUSE BEACH RESORT | All Rights Reserved</p>
</footer>

<script>

function sendBooking(event){
    event.preventDefault();

    document.getElementById("booking-message").innerHTML =
    "✅ Your booking request has been submitted successfully! We will contact you shortly.";
}

</script>

</body>
</html>
```

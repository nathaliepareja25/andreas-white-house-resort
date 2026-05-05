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
        <p>Your Tropical Relaxing Beach Haven in Samal 🌴</p>
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

<!-- rest of your code stays the same -->

</body>
</html>

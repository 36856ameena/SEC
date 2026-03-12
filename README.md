<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>SnoozeCruise</title>

<style>

body{
margin:0;
font-family:Segoe UI, sans-serif;
background:linear-gradient(180deg,#050814,#0b1330);
color:white;
text-align:center;
}

header{
padding:80px 20px;
}

header h1{
font-size:52px;
color:#7aa6ff;
letter-spacing:2px;
}

header p{
color:#a0b4ff;
font-size:18px;
max-width:600px;
margin:auto;
}

button{
margin-top:20px;
padding:12px 30px;
border:none;
border-radius:25px;
background:#7aa6ff;
color:black;
font-weight:bold;
cursor:pointer;
transition:0.3s;
}

button:hover{
box-shadow:0 0 20px #7aa6ff;
transform:scale(1.05);
}

.section{
padding:70px 20px;
}

h2{
color:#7aa6ff;
margin-bottom:40px;
}

.steps{
display:flex;
justify-content:center;
gap:40px;
flex-wrap:wrap;
}

.card{
background:rgba(20,30,70,0.6);
backdrop-filter:blur(10px);
border-radius:20px;
width:260px;
padding:20px;
transition:0.3s;
box-shadow:0 0 20px rgba(0,0,0,0.6);
}

.card:hover{
transform:translateY(-8px);
box-shadow:0 0 30px rgba(122,166,255,0.6);
}

.card img{
width:100%;
border-radius:12px;
}

.card h3{
color:#9dbaff;
margin-top:15px;
}

.card p{
font-size:14px;
color:#d0d8ff;
}

.pricing{
display:flex;
justify-content:center;
gap:40px;
flex-wrap:wrap;
}

.price-card{
background:rgba(20,30,70,0.6);
padding:30px;
border-radius:20px;
width:240px;
transition:0.3s;
}

.price-card:hover{
box-shadow:0 0 30px rgba(122,166,255,0.6);
transform:scale(1.05);
}

.price-card h3{
color:#9dbaff;
}

footer{
margin-top:60px;
padding:20px;
font-size:14px;
color:#8899cc;
}

</style>
</head>

<body>

<header>

<h1>SnoozeCruise</h1>

<p>
SnoozeCruise is a luxury autonomous ride-sharing service designed for digital wellness. 
Instead of sitting in traffic, passengers can relax inside quiet, soundproof nap pods 
and recharge during their commute.
</p>

<button>Book Your Pod</button>

</header>

<section class="section">

<h2>How It Works</h2>

<div class="steps">

<div class="card">
<img src="summon.jpg">
<h3>1. Summon</h3>
<p>
Open the SnoozeCruise app and request a pod instantly. 
The autonomous vehicle arrives at your location within minutes.
</p>
</div>

<div class="card">
<img src="sleep.jpg">
<h3>2. Sleep</h3>
<p>
Step into a comfortable soundproof pod with soft ambient lighting 
and a cozy bed designed for quick rest or relaxation.
</p>
</div>

<div class="card">
<img src="arrive.jpg">
<h3>3. Arrive</h3>
<p>
Wake up refreshed as the pod reaches your destination safely, 
turning your commute into a moment of rest.
</p>
</div>

</div>

</section>

<section class="section">

<h2>Pricing</h2>

<div class="pricing">

<div class="price-card">
<h3>Power Nap</h3>
<p>Perfect for short city rides and quick energy boosts.</p>
<h2>$5</h2>
</div>

<div class="price-card">
<h3>Deep Sleep</h3>
<p>Longer peaceful rides for uninterrupted relaxation.</p>
<h2>$12</h2>
</div>

</div>

</section>

<footer>
© 2026 SnoozeCruise — Digital Wellness Mobility
</footer>

</body>
</html>

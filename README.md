<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Y7 Trader Academy</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#050505;
color:#fff;
overflow-x:hidden;
}

body::before{
content:"";
position:fixed;
top:-200px;
right:-200px;
width:600px;
height:600px;
background:radial-gradient(circle,#D4AF3730,transparent);
filter:blur(80px);
z-index:-1;
}

body::after{
content:"";
position:fixed;
bottom:-200px;
left:-200px;
width:600px;
height:600px;
background:radial-gradient(circle,#D4AF3715,transparent);
filter:blur(100px);
z-index:-1;
}

section{
padding:100px 10%;
}

.hero{
min-height:100vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
}

.hero-content{
max-width:900px;
}

.badge{
display:inline-block;
padding:12px 24px;
border:1px solid rgba(212,175,55,.25);
border-radius:50px;
background:rgba(255,255,255,.04);
backdrop-filter:blur(20px);
color:#D4AF37;
margin-bottom:25px;
}

.hero h1{
font-size:5rem;
font-weight:800;
line-height:1;
margin-bottom:20px;
background:linear-gradient(90deg,#fff,#D4AF37);
-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
}

.hero p{
font-size:1.2rem;
color:#bdbdbd;
line-height:1.8;
margin-bottom:30px;
}

.price{
font-size:3.5rem;
font-weight:800;
color:#D4AF37;
margin:20px 0;
}

.old-price{
font-size:1.4rem;
text-decoration:line-through;
color:#666;
}

.btn{
display:inline-block;
padding:18px 40px;
background:linear-gradient(135deg,#D4AF37,#FFD700);
color:#000;
text-decoration:none;
font-weight:700;
border-radius:14px;
transition:.3s;
}

.btn:hover{
transform:translateY(-5px);
}

.section-title{
text-align:center;
font-size:3rem;
margin-bottom:60px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;
}

.card{
background:rgba(255,255,255,.04);
backdrop-filter:blur(20px);
border:1px solid rgba(255,255,255,.08);
padding:30px;
border-radius:25px;
transition:.4s;
}

.card:hover{
transform:translateY(-10px);
border-color:#D4AF37;
}

.card h3{
color:#D4AF37;
margin-bottom:20px;
}

.card ul{
list-style:none;
}

.card li{
margin:12px 0;
color:#d6d6d6;
}

.bonus{
text-align:center;
}

.bonus-container{
max-width:700px;
margin:auto;
background:rgba(255,255,255,.04);
padding:40px;
border-radius:25px;
border:1px solid rgba(255,255,255,.08);
}

.bonus li{
list-style:none;
margin:15px 0;
font-size:1.1rem;
}

.why{
text-align:center;
}

.why-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
margin-top:40px;
}

.why-box{
background:rgba(255,255,255,.04);
padding:30px;
border-radius:20px;
border:1px solid rgba(255,255,255,.08);
}

.price-section{
text-align:center;
}

.price-card{
max-width:700px;
margin:auto;
background:rgba(255,255,255,.04);
padding:60px;
border-radius:30px;
border:1px solid rgba(212,175,55,.2);
}

.price-card h2{
font-size:3rem;
color:#D4AF37;
}

.footer{
padding:60px 20px;
text-align:center;
border-top:1px solid rgba(255,255,255,.08);
}

.footer h3{
color:#D4AF37;
margin-bottom:15px;
}

.disclaimer{
color:#888;
font-size:.9rem;
margin-top:20px;
}

@media(max-width:768px){

.hero h1{
font-size:3rem;
}

.price{
font-size:2.5rem;
}

.section-title{
font-size:2rem;
}

}

</style>
</head>

<body>

<section class="hero">

<div class="hero-content">

<div class="badge">
🔥 Premium Forex Trading Course
</div>

<h1>Y7 TRADER<br>ACADEMY</h1>

<p>
Master Liquidity Trading & Market Fundamentals.<br>
Learn how to understand market movement, identify liquidity,
manage risk and build trading confidence.
</p>

<div class="old-price">₹9,999</div>
<div class="price">₹4,999</div>

<a href="#enroll" class="btn">ENROLL NOW</a>

</div>

</section>

<section>

<h2 class="section-title">What You'll Learn</h2>

<div class="grid">

<div class="card">
<h3>Trading Fundamentals</h3>
<ul>
<li>✓ What is Forex Trading?</li>
<li>✓ Market Sessions</li>
<li>✓ Currency Pairs</li>
<li>✓ Pips, Lots & Leverage</li>
<li>✓ Trading Platform Setup</li>
</ul>
</div>

<div class="card">
<h3>Market Structure</h3>
<ul>
<li>✓ Trend Identification</li>
<li>✓ Support & Resistance</li>
<li>✓ Trendlines</li>
<li>✓ Key Market Levels</li>
</ul>
</div>

<div class="card">
<h3>Liquidity Concepts</h3>
<ul>
<li>✓ Buy-Side Liquidity</li>
<li>✓ Sell-Side Liquidity</li>
<li>✓ Equal Highs & Lows</li>
<li>✓ Liquidity Sweeps</li>
<li>✓ Market Reactions</li>
</ul>
</div>

<div class="card">
<h3>Trade Execution</h3>
<ul>
<li>✓ Entry Models</li>
<li>✓ Trade Confirmation</li>
<li>✓ Stop Loss Placement</li>
<li>✓ Take Profit Strategies</li>
</ul>
</div>

<div class="card">
<h3>Risk Management</h3>
<ul>
<li>✓ Position Sizing</li>
<li>✓ Risk Management</li>
<li>✓ Trade Management</li>
<li>✓ Capital Protection</li>
</ul>
</div>

<div class="card">
<h3>Trading Psychology</h3>
<ul>
<li>✓ Emotional Discipline</li>
<li>✓ Avoid Overtrading</li>
<li>✓ Consistency Building</li>
<li>✓ Professional Habits</li>
</ul>
</div>

</div>

</section>

<section class="bonus">

<h2 class="section-title">Bonus Resources</h2>

<div class="bonus-container">

<ul>
<li>🎁 Trading Journal Template</li>
<li>🎁 Risk Calculator</li>
<li>🎁 Liquidity Concepts PDF</li>
<li>🎁 Market Analysis Guide</li>
<li>🎁 Weekly Market Reviews</li>
</ul>

</div>

</section>

<section class="why">

<h2 class="section-title">Why Choose Y7 Trader Academy?</h2>

<div class="why-grid">

<div class="why-box">
✔ Beginner Friendly
</div>

<div class="why-box">
✔ Practical Market Examples
</div>

<div class="why-box">
✔ Community Support
</div>

<div class="why-box">
✔ Lifetime Access
</div>

</div>

</section>

<section id="enroll" class="price-section">

<div class="price-card">

<h2>₹4,999</h2>

<p style="margin:20px 0;color:#bbb;">
One-Time Payment • Lifetime Access
</p>

<a href="#" class="btn">START LEARNING TODAY</a>

</div>

</section>

<footer class="footer">

<h3>Y7 TRADER ACADEMY</h3>

<p>
Learn the Basics. Understand Liquidity. Trade with Confidence.
</p>

<p class="disclaimer">
Trading involves risk. This course is for educational purposes only and does not guarantee profits.
</p>

</footer>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ali's BMW Garage</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap');

*{margin:0;padding:0;box-sizing:border-box;}
body{font-family:'Poppins',sans-serif;background:#02040f;color:#f5f5f5;scroll-behavior:smooth;}

header{background:linear-gradient(90deg,#00143b,#0047ab);padding:25px;text-align:center;box-shadow:0 4px 15px rgba(0,100,255,0.3);}
header h1{font-size:3em;color:#00b0ff;letter-spacing:2px;}
header p{font-size:1.1em;color:#a0c4ff;}

nav{background:#030c1b;padding:15px 0;text-align:center;position:sticky;top:0;z-index:100;box-shadow:0 2px 10px rgba(0,0,0,0.4);}
nav a{color:#ccc;text-decoration:none;margin:0 20px;font-weight:bold;transition:0.3s;}
nav a:hover{color:#00b0ff;text-shadow:0 0 8px #00b0ff;}

.hero{position:relative;height:90vh;display:flex;align-items:center;justify-content:center;text-align:center;color:#fff;overflow:hidden;}
.hero video{position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover;z-index:0;}
.hero h2{position:relative;font-size:3.5em;background:rgba(0,0,0,0.6);padding:25px 60px;border-radius:15px;backdrop-filter:blur(6px);box-shadow:0 0 30px rgba(0,160,255,0.4);z-index:1;}

section{padding:80px 20px;text-align:center;}
section h2{color:#00b0ff;font-size:2.2em;margin-bottom:40px;position:relative;}
section h2::after{content:'';width:100px;height:3px;background:#00b0ff;position:absolute;bottom:-15px;left:50%;transform:translateX(-50%);border-radius:5px;}

.models{display:flex;flex-wrap:wrap;justify-content:center;gap:40px;}
.card{background:linear-gradient(145deg,#0b1224,#0f1930);width:320px;border-radius:15px;overflow:hidden;box-shadow:0 0 20px rgba(0,160,255,0.1);transition:all 0.4s;}
.card:hover{transform:translateY(-10px) scale(1.03);box-shadow:0 0 25px rgba(0,160,255,0.5);}
.card img{width:100%;height:200px;object-fit:cover;}
.card h3{color:#00b0ff;margin-top:15px;}
.card p{padding:12px 20px 30px;color:#cdd6f4;font-size:0.95em;}

.features{display:flex;flex-wrap:wrap;justify-content:center;gap:40px;margin-top:40px;}
.feature-card{background:#0f1930;width:300px;padding:20px;border-radius:15px;box-shadow:0 0 15px rgba(0,160,255,0.1);transition:0.3s;}
.feature-card:hover{transform:translateY(-10px);box-shadow:0 0 20px rgba(0,160,255,0.4);}
.feature-card h3{color:#00b0ff;margin-bottom:10px;}
.feature-card p{color:#cdd6f4;font-size:0.95em;}

.cta{margin:50px 0;}
.cta button{background:#00b0ff;color:#fff;font-size:1.1em;padding:15px 35px;border:none;border-radius:10px;cursor:pointer;transition:0.3s;}
.cta button:hover{background:#0081c2;box-shadow:0 0 15px rgba(0,160,255,0.5);}

#contact a{color:#00b0ff;text-decoration:none;}
footer{background:#010817;text-align:center;padding:30px;font-size:0.9em;color:#888;border-top:1px solid #003a80;}

@media(max-width:900px){.models,.features{flex-direction:column;align-items:center;}}
</style>
</head>
<body>

<header>
<h1>Ali's BMW Garage</h1>
<p>Where Performance Meets Perfection</p>
</header>

<nav>
<a href="#home">Home</a>
<a href="#models">Models</a>
<a href="#features">Features</a>
<a href="#contact">Contact</a>
</nav>

<section class="hero" id="home">
<video autoplay muted loop>
<source src="https://www.w3schools.com/howto/rain.mp4" type="video/mp4">
Your browser does not support HTML video.
</video>
<h2>Experience the Power of BMW</h2>
</section>

<section id="models">
<h2>Our BMW Models</h2>
<div class="models">
<div class="card">
<img src="https://cdn.bmwblog.com/wp-content/uploads/2021/06/2021-bmw-330i-m-sport-12-1200x800.jpg" alt="BMW 3 Series">
<h3>BMW 3 Series</h3>
<p>Timeless design, advanced tech, and dynamic performance — the BMW 3 Series defines sporty elegance.</p>
</div>
<div class="card">
<img src="https://cdn.bmwblog.com/wp-content/uploads/2021/06/2021-bmw-540i-4-1200x800.jpg" alt="BMW 5 Series">
<h3>BMW 5 Series</h3>
<p>The perfect fusion of business class luxury and heart-racing power, built for those who demand more.</p>
</div>
<div class="card">
<img src="https://cdn.bmwblog.com/wp-content/uploads/2021/06/2021-bmw-x6-m50i-4-1200x800.jpg" alt="BMW X6 M">
<h3>BMW X6 M</h3>
<p>Bold. Aggressive. Unstoppable. The BMW X6 M brings track-level performance to the SUV world.</p>
</div>
</div>
</section>

<section id="features">
<h2>BMW Features</h2>
<div class="features">
<div class="feature-card">
<h3>Driving Dynamics</h3>
<p>Advanced handling, adaptive suspension, and precise steering for a dynamic drive.</p>
</div>
<div class="feature-card">
<h3>Luxury Interior</h3>
<p>Premium materials, customizable displays, and comfort-focused technology.</p>
</div>
<div class="feature-card">
<h3>Safety Technology</h3>
<p>Smart safety systems, collision prevention, and driver assistance features.</p>
</div>
</div>
</section>

<section class="cta">
<button>Book a Test Drive</button>
</section>

<section id="contact">
<h2>Contact Us</h2>
<p>Email: <a href="mailto:info@alisbmwgarage.com">info@alisbmwgarage.com</a></p>
<p>Follow us for BMW updates and news!</p>
</section>

<footer>
<p>© 2025 Ali's BMW Garage | Built with 💙 and speed | Hosted on GitHub Pages</p>
</footer>

</body>
</html>


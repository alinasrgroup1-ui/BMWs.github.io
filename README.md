<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ali's BMW Garage</title>

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap');

    * {margin:0; padding:0; box-sizing:border-box;}
    body {font-family:'Poppins', sans-serif; background-color:#02040f; color:#f5f5f5; overflow-x:hidden;}

    header {background: linear-gradient(90deg, #00143b, #0047ab); padding:30px; text-align:center; box-shadow:0 4px 15px rgba(0,100,255,0.3); animation: fadeIn 1.5s ease;}
    header h1 {font-size:2.8em; color:#00b0ff; letter-spacing:2px;}
    header p {font-size:1.1em; color:#a0c4ff;}

    nav {background-color:#030c1b; padding:12px 0; text-align:center; position:sticky; top:0; z-index:100; box-shadow:0 2px 10px rgba(0,0,0,0.4); animation: slideDown 1s ease;}
    nav a {color:#ccc; text-decoration:none; margin:0 20px; font-weight:bold; transition:color 0.3s, text-shadow 0.3s;}
    nav a:hover {color:#00b0ff; text-shadow:0 0 8px #00b0ff;}

    .hero {position:relative; height:75vh; display:flex; align-items:center; justify-content:center; text-align:center; color:#fff; text-shadow:0 0 20px #000; overflow:hidden;}
    .hero video {position:absolute; top:0; left:0; width:100%; height:100%; object-fit:cover; z-index:0;}
    .hero h2 {position:relative; font-size:3em; background:rgba(0,0,0,0.6); padding:20px 50px; border-radius:15px; backdrop-filter:blur(6px); box-shadow:0 0 25px rgba(0,160,255,0.3); z-index:1; animation: zoomIn 2s ease;}

    section {padding:60px 20px; text-align:center;}
    section h2 {color:#00b0ff; font-size:2em; margin-bottom:30px; position:relative;}
    section h2::after {content:''; width:80px; height:3px; background:#00b0ff; position:absolute; bottom:-10px; left:50%; transform:translateX(-50%); border-radius:5px;}

    .models {display:flex; flex-wrap:wrap; justify-content:center; gap:35px;}
    .card {background:linear-gradient(145deg, #0b1224, #0f1930); width:300px; border-radius:15px; overflow:hidden; box-shadow:0 0 15px rgba(0,160,255,0.1); transition:all 0.4s ease; animation: fadeUp 1s ease;}
    .card:hover {transform:translateY(-10px) scale(1.02); box-shadow:0 0 20px rgba(0,160,255,0.4);}
    .card img {width:100%; height:180px; object-fit:cover;}
    .card h3 {color:#00b0ff; margin-top:15px;}
    .card p {padding:10px 20px 25px; color:#cdd6f4; font-size:0.95em;}

    footer {background:#010817; text-align:center; padding:25px; font-size:0.9em; color:#888; border-top:1px solid #003a80;}

    @keyframes fadeIn {from{opacity:0;} to{opacity:1;}}
    @keyframes slideDown {from{transform:translateY(-30px); opacity:0;} to{transform:translateY(0); opacity:1;}}
    @keyframes fadeUp {from{transform:translateY(40px); opacity:0;} to{transform:translateY(0); opacity:1;}}
    @keyframes zoomIn {from{transform:scale(1.05); opacity:0;} to{transform:scale(1); opacity:1;}}
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
    <a href="#contact">Contact</a>
  </nav>

  <!-- Hero Section with Video -->
  <section class="hero" id="home">
    <video autoplay muted loop>
      <source src="https://www.w3schools.com/howto/rain.mp4" type="video/mp4">
      Your browser does not support HTML video.
    </video>
    <h2>Experience the Power of BMW</h2>
  </section>

  <section id="models">
    <h2>Featured BMW Models</h2>
    <div class="models">
      <div class="card">
        <img src="https://cdn.bmwblog.com/wp-content/uploads/2021/06/2021-bmw-330i-m-sport-12-1200x800.jpg" alt="BMW 3 Series">
        <h3>BMW 3 Series</h3>
        <p>Timeless design, advanced tech, and dynamic perfo

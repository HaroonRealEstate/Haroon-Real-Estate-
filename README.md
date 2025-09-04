<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Haroon Real Estate & Builders</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: linear-gradient(90deg, #004d40, #00796b);
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
    }
    nav {
      margin-top: 10px;
    }
    nav a {
      color: #fff;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1505691938895-1758d7feb511?auto=format&fit=crop&w=1350&q=80') no-repeat center/cover;
      height: 400px;
      display: flex;
      justify-content: center;
      align-items: center;
      color: #fff;
      text-shadow: 0 2px 4px rgba(0,0,0,0.7);
    }
    .hero h2 {
      font-size: 2.5rem;
      background: rgba(0,0,0,0.5);
      padding: 15px;
      border-radius: 10px;
    }
    .section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .section h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #00796b;
    }
    .cards {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .card {
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      padding: 20px;
      width: 300px;
      text-align: center;
    }
    .card h3 {
      margin: 10px 0;
      color: #004d40;
    }
    footer {
      background: #004d40;
      color: #fff;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
    .btn {
      display: inline-block;
      margin-top: 15px;
      padding: 10px 20px;
      background: #00796b;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
    }
    .btn:hover {
      background: #004d40;
    }
  </style>
</head>
<body>
  <header>
    <h1>Haroon Real Estate & Builders</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Welcome to Haroon Heights – A Modern Lifestyle in Faisal Hills</h2>
  </section>

  <section class="section" id="about">
    <h2>About Us</h2>
    <p>Haroon Real Estate & Builders is a trusted name in modern construction and real estate solutions. Our latest project, Haroon Heights in Faisal Hills B Block, is a 7-floor apartment building offering 1, 2, and 3 bedroom apartments – each designed with comfort and style.</p>
  </section>

  <section class="section" id="projects">
    <h2>Our Apartments</h2>
    <div class="cards">
      <div class="card">
        <h3>1 Bedroom Apartment</h3>
        <p>540 sq ft with attached bathroom and modern design.</p>
        <a class="btn" href="#contact">Book Now</a>
      </div>
      <div class="card">
        <h3>2 Bedroom Apartment</h3>
        <p>1080 sq ft, spacious living, ideal for small families.</p>
        <a class="btn" href="#contact">Book Now</a>
      </div>
      <div class="card">
        <h3>3 Bedroom Apartment</h3>
        <p>1172 sq ft, luxury living with all modern amenities.</p>
        <a class="btn" href="#contact">Book Now</a>
      </div>
    </div>
  </section>

  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <p>📞 Phone: +92 300 1234567</p>
    <p>📍 Office: Faisal Hills B Block, Taxila, Pakistan</p>
    <p>💬 WhatsApp: <a href="https://wa.me/923001234567" target="_blank">Chat Now</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Haroon Real Estate & Builders. All rights reserved.</p>
  </footer>
</body>
</html>

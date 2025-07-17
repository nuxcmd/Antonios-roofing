<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Elite Builders & Real Estate</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Urbanist:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Urbanist', sans-serif;
    }

    body {
      background-color: #f6f6f6;
      color: #222;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(to right, #2c3e50, #34495e);
      color: #fff;
      padding: 1.5rem 3rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 100;
    }

    header h1 {
      font-size: 1.8rem;
      font-weight: 800;
    }

    nav a {
      color: #fff;
      margin-left: 2rem;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #f39c12;
    }

    .hero {
      background-image: url('https://images.unsplash.com/photo-1570129477492-45c003edd2be');
      background-size: cover;
      background-position: center;
      height: 85vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
      padding: 2rem;
    }

    .hero h2 {
      font-size: 3rem;
      font-weight: 800;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.6);
    }

    .section {
      padding: 4rem 2rem;
      max-width: 1100px;
      margin: 0 auto;
    }

    .section h3 {
      font-size: 2rem;
      margin-bottom: 1.5rem;
      text-align: center;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
    }

    .card {
      background: #fff;
      padding: 1.5rem;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    }

    .card h4 {
      font-size: 1.4rem;
      margin-bottom: 0.8rem;
    }

    .card p {
      font-size: 0.95rem;
    }

    footer {
      background: #2c3e50;
      color: #fff;
      padding: 2rem;
      text-align: center;
      margin-top: 3rem;
    }
  </style>
</head>

<body>
  <header>
    <h1>Elite Builders</h1>
    <nav>
      <a href="#services">Services</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Your Vision, Our Construction – Real Estate Excellence</h2>
  </section>

  <section class="section" id="services">
    <h3>Our Services</h3>
    <div class="cards">
      <div class="card">
        <h4>Custom Home Building</h4>
        <p>We create luxurious, tailored homes designed to match your dreams.</p>
      </div>
      <div class="card">
        <h4>Commercial Development</h4>
        <p>Efficient, elegant business structures for long-term investment and growth.</p>
      </div>
      <div class="card">
        <h4>Property Renovation</h4>
        <p>Transforming existing spaces with quality upgrades and remodeling.</p>
      </div>
    </div>
  </section>

  <section class="section" id="projects">
    <h3>Featured Projects</h3>
    <div class="cards">
      <div class="card">
        <h4>Hilltop Villas</h4>
        <p>A serene modern living community with luxury villas and scenic views.</p>
      </div>
      <div class="card">
        <h4>Skyline Towers</h4>
        <p>High-rise residential towers with state-of-the-art amenities in the heart of the city.</p>
      </div>
      <div class="card">
        <h4>GreenPoint Offices</h4>
        <p>Eco-friendly commercial complex promoting sustainability and smart workspaces.</p>
      </div>
    </div>
  </section>

  <section class="section" id="contact">
    <h3>Contact Us</h3>
    <div style="text-align:center">
      <p>Email: contact@elitebuilders.com</p>
      <p>Phone: (210) 555-0123</p>
      <p>Location: San Antonio, TX</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Elite Builders & Real Estate. All rights reserved.</p>
  </footer>
</body>

</html>


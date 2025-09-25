<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Snaeland Travel</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Segoe UI", sans-serif;
    }

    body {
      background: #f8f8f8;
      color: #333;
      line-height: 1.6;
    }

    /* Navbar */
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 50px;
      background: #fff;
      position: sticky;
      top: 0;
      z-index: 1000;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    nav .logo {
      font-size: 1.3rem;
      font-weight: bold;
      color: #0083b0;
    }
    nav ul {
      display: flex;
      gap: 20px;
      list-style: none;
    }
    nav ul li a {
      text-decoration: none;
      color: #333;
      font-weight: 500;
    }

    /* Hero Section */
    .hero {
      position: relative;
      background: url("https://images.unsplash.com/photo-1501785888041-af3ef285b470") no-repeat center/cover;
      height: 80vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
      text-align: center;
    }
    .hero-content {
      background: rgba(0,0,0,0.5);
      padding: 30px;
      border-radius: 10px;
    }
    .hero h1 {
      font-size: 2.8rem;
      margin-bottom: 15px;
    }
    .hero p {
      font-size: 1.2rem;
      max-width: 600px;
      margin: 0 auto;
    }

    /* Stats */
    .stats {
      display: flex;
      justify-content: space-around;
      padding: 40px 20px;
      background: #fff;
    }
    .stat {
      text-align: center;
    }
    .stat h2 {
      color: #0083b0;
      font-size: 2rem;
    }

    /* Destinations */
    .section {
      padding: 60px 20px;
      max-width: 1200px;
      margin: auto;
    }
    .section h2 {
      text-align: center;
      margin-bottom: 30px;
      color: #0083b0;
      font-size: 2rem;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
    }
    .card {
      background: #fff;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
    .card:hover {
      transform: scale(1.03);
    }
    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .card h3 {
      margin: 15px;
      font-size: 1.2rem;
    }
    .card p {
      margin: 0 15px 20px;
      font-size: 0.95rem;
      color: #555;
    }

    /* Footer */
    footer {
      background: #111;
      color: #fff;
      padding: 40px 20px;
      text-align: center;
    }
    footer h1 {
      font-size: 2rem;
      margin-bottom: 10px;
      letter-spacing: 2px;
    }
    footer p {
      font-size: 0.9rem;
      opacity: 0.8;
    }

    /* Responsive */
    @media (max-width: 768px) {
      nav {
        flex-direction: column;
        gap: 15px;
      }
      .hero h1 {
        font-size: 2rem;
      }
      .stats {
        flex-direction: column;
        gap: 20px;
      }
    }
  </style>
</head>
<body>
  <!-- Navbar -->
  <nav>
    <div class="logo">Snaeland</div>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Destinations</a></li>
      <li><a href="#">Packages</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-content">
      <h1>Weaving Your Dreams into Unforgettable Adventures</h1>
      <p>Discover breathtaking landscapes, vibrant cultures, and tailor-made travel experiences around the world.</p>
    </div>
  </section>

  <!-- Stats -->
  <section class="stats">
    <div class="stat">
      <h2>95%</h2>
      <p>Happy Travelers</p>
    </div>
    <div class="stat">
      <h2>72+</h2>
      <p>Countries Covered</p>
    </div>
    <div class="stat">
      <h2>250+</h2>
      <p>Trips Organized</p>
    </div>
  </section>

  <!-- Destinations -->
  <section class="section">
    <h2>Popular Destinations</h2>
    <div class="grid">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee" alt="Mountains">
        <h3>Majestic Mountains</h3>
        <p>Experience hiking, camping, and the fresh air of natureâs tallest wonders.</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e" alt="Beach">
        <h3>Golden Beaches</h3>
        <p>Relax and rejuvenate with golden sands and turquoise waters.</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1526778548025-fa2f459cd5c1" alt="City">
        <h3>Urban Escapes</h3>
        <p>Explore iconic skylines, nightlife, and cultural hotspots.</p>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <h1>SNAELAND</h1>
    <p>Â© 2025 Snaeland Travel. All Rights Reserved.</p>
  </footer>
</body>
</html>

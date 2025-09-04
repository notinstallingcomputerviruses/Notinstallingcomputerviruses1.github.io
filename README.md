<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PC Builder Showcase</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #0f0f0f;
      color: #f5f5f5;
    }
    header {
      text-align: center;
      padding: 3rem 1rem;
      background: linear-gradient(135deg, #1e1e1e, #3a3a3a);
    }
    header h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }
    header p {
      font-size: 1.2rem;
      color: #bbb;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
      padding: 2rem;
    }
    .card {
      background: #1c1c1c;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 4px 15px rgba(0,0,0,0.5);
      transition: transform 0.2s ease;
      cursor: pointer;
      text-decoration: none;
      color: inherit;
    }
    .card:hover {
      transform: scale(1.05);
    }
    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .card h3 {
      margin: 1rem;
      font-size: 1.3rem;
    }
    .card p {
      margin: 0 1rem 1rem;
      font-size: 0.95rem;
      color: #ccc;
    }
    footer {
      text-align: center;
      padding: 1.5rem;
      background: #111;
      font-size: 0.9rem;
      color: #777;
    }
  </style>
</head>
<body>
  <header>
    <h1>PC Builder Showcase</h1>
    <p>Explore the coolest custom PC builds from around the world</p>
  </header>

  <section class="gallery">
    <a href="pc1.html" class="card">
      <img src="https://i.imgur.com/z4d4kWk.jpg" alt="RGB Gaming PC">
      <h3>RGB Gaming Beast</h3>
      <p>Featuring RTX 4090, Ryzen 9, and custom water cooling.</p>
    </a>
    <a href="pc2.html" class="card">
      <img src="https://i.imgur.com/4AiXzf8.jpg" alt="Minimalist PC">
      <h3>Minimalist White Build</h3>
      <p>Clean white aesthetic with tempered glass and silent cooling.</p>
    </a>
    <a href="pc3.html" class="card">
      <img src="https://i.imgur.com/6Iej2c3.jpg" alt="Compact PC">
      <h3>Compact Powerhouse</h3>
      <p>Small form factor with a big punch — RTX 3080 and liquid-cooled i7.</p>
    </a>
    <a href="pc4.html" class="card">
      <img src="https://i.imgur.com/XOON6GV.jpg" alt="Workstation PC">
      <h3>Ultimate Workstation</h3>
      <p>Designed for creators — 128GB RAM, Threadripper CPU, dual GPUs.</p>
    </a>
  </section>

  <footer>
    © 2025 PC Builder Showcase | Built with ❤️ for PC enthusiasts
  </footer>
</body>
</html>

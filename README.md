<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bisht Construction LLC</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; line-height: 1.6; }
    header { background: #2c3e50; color: white; padding: 20px; text-align: center; }
    header h1 { margin: 0; }
    nav { margin-top: 10px; }
    nav a { color: white; text-decoration: none; margin: 0 10px; font-weight: bold; }
    .hero { background: url('https://via.placeholder.com/1200x400') no-repeat center center/cover; color: white; text-align: center; padding: 100px 20px; }
    .hero h2 { font-size: 2.5rem; }
    .btn { background: #e67e22; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px; }
    section { padding: 40px 20px; max-width: 1000px; margin: auto; }
    .services, .gallery, .testimonials { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
    .card { border: 1px solid #ccc; padding: 20px; border-radius: 8px; background: #f9f9f9; }
    footer { background: #2c3e50; color: white; text-align: center; padding: 20px; margin-top: 20px; }
  </style>
</head>
<body>

  <header>
    <h1>Bisht Construction LLC</h1>
    <nav>
      <a href="#services">Services</a>
      <a href="#gallery">Gallery</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Reliable Construction & Remodeling in Your City</h2>
    <p>Licensed, insured, and trusted for over 10 years.</p>
    <a href="#contact" class="btn">Request a Free Quote</a>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="card">🏠 <strong>Home Remodeling</strong><br>Kitchens, bathrooms, basements</div>
      <div class="card">🔨 <strong>Repairs & Renovations</strong><br>Interior & exterior</div>
      <div class="card">🪚 <strong>Custom Carpentry</strong><br>Decks, cabinets, framing</div>
      <div class="card">🏗️ <strong>New Construction</strong><br>Additions & builds</div>
    </div>
  </section>

  <section id="gallery">
    <h2>Project Gallery</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/300" alt="Project 1">
      <img src="https://via.placeholder.com/300" alt="Project 2">
      <img src="https://via.placeholder.com/300" alt="Project 3">
    </div>
  </section>

  <section id="about">
    <h2>Why Choose Us</h2>
    <ul>
      <li>✅ Licensed & Insured</li>
      <li>✅ On-Time & On-Budget</li>
      <li>✅ 100% Satisfaction Guarantee</li>
      <li>✅ Free Estimates</li>
    </ul>
  </section>

  <section id="testimonials">
    <h2>Customer Testimonials</h2>
    <div class="testimonials">
      <div class="card">“They remodeled our kitchen beautifully. Highly recommended!” – Sarah, MD</div>
      <div class="card">“Professional, honest, and affordable. Great job on my deck.” – John, VA</div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>📞 (555) 123-4567 | ✉️ info@bishtconstruction.com</p>
    <form>
      <input type="text" placeholder="Your Name" required><br><br>
      <input type="email" placeholder="Your Email" required><br><br>
      <textarea placeholder="Your Project Details" required></textarea><br><br>
      <button type="submit" class="btn">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Bisht Construction LLC | All Rights Reserved</p>
  </footer>

</body>
</html>

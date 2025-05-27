<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>THREADNOVA | Redefining Style</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f5f5f5;
      color: #333;
    }
    header {
      background: #000;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background: #222;
      padding: 10px 0;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1600185365483-26c6a509a3c1?ixlib=rb-4.0.3&auto=format&fit=crop&w=1950&q=80') no-repeat center center/cover;
      height: 80vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-align: center;
      flex-direction: column;
      padding: 0 20px;
    }
    .hero h1 {
      font-size: 4em;
      margin: 0;
    }
    .hero p {
      font-size: 1.5em;
      max-width: 600px;
      margin: 10px 0 0 0;
    }
    .btn {
      background: #000;
      color: #fff;
      padding: 15px 30px;
      text-decoration: none;
      font-size: 1.2em;
      margin-top: 20px;
      border-radius: 5px;
      display: inline-block;
      transition: background 0.3s ease;
    }
    .btn:hover {
      background: #444;
    }
    .section {
      padding: 60px 20px;
      text-align: center;
      max-width: 1000px;
      margin: 0 auto;
    }
    .section h2 {
      font-size: 2.5em;
      margin-bottom: 20px;
    }
    .section p {
      font-size: 1.2em;
      line-height: 1.6;
      max-width: 700px;
      margin: 0 auto;
      color: #555;
    }
    .collection-items {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      margin-top: 40px;
    }
    .item {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      width: 280px;
      overflow: hidden;
      text-align: left;
    }
    .item img {
      width: 100%;
      display: block;
    }
    .item-content {
      padding: 15px;
    }
    .item-content h3 {
      margin: 0 0 10px 0;
      font-size: 1.4em;
    }
    .item-content p {
      margin: 0;
      color: #666;
      font-size: 1em;
    }
    footer {
      background: #000;
      color: #fff;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>THREADNOVA</h1>
    <p>Redefining Style. Inspiring Confidence.</p>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#collection">Collection</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
  <div id="home" class="hero">
    <h1>Elevate Your Wardrobe</h1>
    <p>Discover bold, modern fashion designed to make you stand out.</p>
    <a href="#collection" class="btn">Shop the Collection</a>
  </div>

  <section id="collection" class="section">
    <h2>Our Collection</h2>
    <p>Handpicked styles that combine quality and trend-setting designs.</p>
    <div class="collection-items">
      <div class="item">
        <img src="https://images.unsplash.com/photo-1521335629791-ce4aec67dd49?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Stylish Jacket" />
        <div class="item-content">
          <h3>Modern Jacket</h3>
          <p>Lightweight and perfect for any occasion.</p>
        </div>
      </div>
      <div class="item">
        <img src="https://images.unsplash.com/photo-1512436991641-6745cdb1723f?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Classic Shirt" />
        <div class="item-content">
          <h3>Classic Shirt</h3>
          <p>Timeless design for everyday elegance.</p>
        </div>
      </div>
      <div class="item">
        <img src="https://images.unsplash.com/photo-1495121605193-b116b5b09a74?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Casual Trousers" />
        <div class="item-content">
          <h3>Casual Trousers</h3>
          <p>Comfort and style combined.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="about" class="section">
    <h2>About THREADNOVA</h2>
    <p>THREADNOVA is dedicated to bringing you innovative fashion that redefines style and inspires confidence. Our mission is to create pieces that empower you to express your unique identity.</p>
  </section>

  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <p>Questions? Suggestions? We'd love to hear from you!</p>
    <p>Email us at <a href="mailto:contact@threadnova.com">contact@threadnova.com</a></p>
  </section>

  <footer>
    &copy; 2025 THREADNOVA. All rights reserved.
  </footer>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>THREADNOVA | Redefining Style</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f5f5f5;
      color: #333;
    }
    header {
      background: #000;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background: #222;
      padding: 10px 0;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1600185365483-26c6a509a3c1?ixlib=rb-4.0.3&auto=format&fit=crop&w=1950&q=80') no-repeat center center/cover;
      height: 80vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-align: center;
      flex-direction: column;
      padding: 0 20px;
    }
    .hero h1 {
      font-size: 4em;
      margin: 0;
    }
    .hero p {
      font-size: 1.5em;
      max-width: 600px;
      margin: 10px 0 0 0;
    }
    .btn {
      background: #000;
      color: #fff;
      padding: 15px 30px;
      text-decoration: none;
      font-size: 1.2em;
      margin-top: 20px;
      border-radius: 5px;
      display: inline-block;
      transition: background 0.3s ease;
    }
    .btn:hover {
      background: #444;
    }
    .section {
      padding: 60px 20px;
      text-align: center;
      max-width: 1000px;
      margin: 0 auto;
    }
    .section h2 {
      font-size: 2.5em;
      margin-bottom: 20px;
    }
    .section p {
      font-size: 1.2em;
      line-height: 1.6;
      max-width: 700px;
      margin: 0 auto;
      color: #555;
    }
    .collection-items {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      margin-top: 40px;
    }
    .item {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      width: 280px;
      overflow: hidden;
      text-align: left;
    }
    .item img {
      width: 100%;
      display: block;
    }
    .item-content {
      padding: 15px;
    }
    .item-content h3 {
      margin: 0 0 10px 0;
      font-size: 1.4em;
    }
    .item-content p {
      margin: 0;
      color: #666;
      font-size: 1em;
    }
    footer {
      background: #000;
      color: #fff;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>THREADNOVA</h1>
    <p>Redefining Style. Inspiring Confidence.</p>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#collection">Collection</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
  <div id="home" class="hero">
    <h1>Elevate Your Wardrobe</h1>
    <p>Discover bold, modern fashion designed to make you stand out.</p>
    <a href="#collection" class="btn">Shop the Collection</a>
  </div>

  <section id="collection" class="section">
    <h2>Our Collection</h2>
    <p>Handpicked styles that combine quality and trend-setting designs.</p>
    <div class="collection-items">
      <div class="item">
        <img src="https://images.unsplash.com/photo-1521335629791-ce4aec67dd49?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Stylish Jacket" />
        <div class="item-content">
          <h3>Modern Jacket</h3>
          <p>Lightweight and perfect for any occasion.</p>
        </div>
      </div>
      <div class="item">
        <img src="https://images.unsplash.com/photo-1512436991641-6745cdb1723f?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Classic Shirt" />
        <div class="item-content">
          <h3>Classic Shirt</h3>
          <p>Timeless design for everyday elegance.</p>
        </div>
      </div>
      <div class="item">
        <img src="https://images.unsplash.com/photo-1495121605193-b116b5b09a74?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Casual Trousers" />
        <div class="item-content">
          <h3>Casual Trousers</h3>
          <p>Comfort and style combined.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="about" class="section">
    <h2>About THREADNOVA</h2>
    <p>THREADNOVA is dedicated to bringing you innovative fashion that redefines style and inspires confidence. Our mission is to create pieces that empower you to express your unique identity.</p>
  </section>

  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <p>Questions? Suggestions? We'd love to hear from you!</p>
    <p>Email us at <a href="mailto:contact@threadnova.com">contact@threadnova.com</a></p>
  </section>

  <footer>
    &copy; 2025 THREADNOVA. All rights reserved.
  </footer>
</body>
</html>

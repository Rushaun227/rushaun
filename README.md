<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ffirst Clothing</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
    }
    header {
      background-color: #111;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #333;
      display: flex;
      justify-content: center;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
    }
    nav a:hover {
      background-color: #555;
    }
    .section {
      padding: 40px 20px;
    }
    .product-grid {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      gap: 20px;
    }
    .product {
      background: white;
      padding: 20px;
      border-radius: 8px;
      width: 250px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .reviews {
      background-color: #fff;
      padding: 20px;
      border-top: 1px solid #ccc;
    }
    .review {
      margin-bottom: 20px;
      border-bottom: 1px solid #ddd;
      padding-bottom: 10px;
    }
    footer {
      text-align: center;
      background: #111;
      color: white;
      padding: 10px;
    }
    form {
      display: flex;
      flex-direction: column;
      max-width: 400px;
      margin: 0 auto;
    }
    input, textarea {
      padding: 10px;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>

<header>
  <h1>ffirst Clothing</h1>
  <p>Fashion made bold. Style that speaks.</p>
</header>

<nav>
  <a href="#men">Men</a>
  <a href="#women">Women</a>
  <a href="#accessories">Accessories</a>
  <a href="#reviews">Reviews</a>
  <a href="#contact">Contact</a>
</nav>

<section class="section" id="men">
  <h2>Men's Collection</h2>
  <div class="product-grid">
    <div class="product">
      <h3>Classic Denim Jacket</h3>
      <p>$65.00</p>
    </div>
    <div class="product">
      <h3>Black Graphic Tee</h3>
      <p>$30.00</p>
    </div>
    <div class="product">
      <h3>Jogger Pants</h3>
      <p>$45.00</p>
    </div>
  </div>
</section>

<section class="section" id="women">
  <h2>Women's Collection</h2>
  <div class="product-grid">
    <div class="product">
      <h3>Crop Hoodie</h3>
      <p>$40.00</p>
    </div>
    <div class="product">
      <h3>High-Waisted Jeans</h3>
      <p>$55.00</p>
    </div>
    <div class="product">
      <h3>Summer Dress</h3>
      <p>$50.00</p>
    </div>
  </div>
</section>

<section class="section" id="accessories">
  <h2>Accessories</h2>
  <div class="product-grid">
    <div class="product">
      <h3>Beanie Hat</h3>
      <p>$15.00</p>
    </div>
    <div class="product">
      <h3>Crossbody Bag</h3>
      <p>$35.00</p>
    </div>
    <div class="product">
      <h3>Leather Belt</h3>
      <p>$25.00</p>
    </div>
  </div>
</section>

<section class="section reviews" id="reviews">
  <h2>What Our Customers Say</h2>
  <div class="review">
    <strong>Alex M.</strong> - "The quality is top-notch and delivery was super fast!"
  </div>
  <div class="review">
    <strong>Samantha R.</strong> - "Love my new crop hoodie. Can't wait to buy more from ffirst!"
  </div>
  <div class="review">
    <strong>Jordan K.</strong> - "Trendy and affordable. This brand is going places."
  </div>
</section>

<section class="section" id="contact">
  <h2>Contact Us</h2>
  <form>
    <input type="text" placeholder="Your Name" required>
    <input type="email" placeholder="Your Email" required>
    <textarea rows="5" placeholder="Your Message"></textarea>
    <input type="submit" value="Send Message">
  </form>
</section>

<footer>
  <p>&copy; 2025 ffirst Clothing. All rights reserved.</p>
</footer>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cycle365 - Bicycle Parts Shop</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f8f9fa;
    }
    header {
      background-color: #2c3e50;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .container {
      padding: 20px;
    }
    .info {
      margin-bottom: 30px;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 20px;
    }
    .product {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      padding: 15px;
      text-align: center;
    }
    .product img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 5px;
    }
    .contact {
      margin-top: 40px;
      background-color: #ecf0f1;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
    }
    .map {
      margin-top: 20px;
      text-align: center;
    }
    .whatsapp {
      display: inline-block;
      margin-top: 15px;
      padding: 10px 20px;
      background-color: #25D366;
      color: white;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
    }
    footer {
      text-align: center;
      padding: 10px;
      background-color: #2c3e50;
      color: white;
    }
  </style>
</head>
<body>
  <header>
    <h1>Cycle365</h1>
    <p>Your Trusted Bicycle Parts Shop in Mohammadpur</p>
  </header>
  <div class="container">
    <div class="info">
      <h2>Shop Info</h2>
      <p><strong>Address:</strong> 20, Niribili Gate, Near Shia Mosque, Mohammadpur, Dhaka</p>
      <p><strong>Open Hours:</strong> 10:00 AM – 10:00 PM (Every Day)</p>
    </div>

    <div class="products">
      <div class="product">
        <img src="https://i.imgur.com/Wb1hlhL.jpg" alt="Helmet">
        <h3>Safety Helmet</h3>
        <p>BDT 330</p>
      </div>
      <div class="product">
        <img src="https://i.imgur.com/0ErlOek.jpg" alt="Cable Lock">
        <h3>Zhongli Cable Lock</h3>
        <p>BDT 423</p>
      </div>
      <div class="product">
        <img src="https://i.imgur.com/y0rYwlo.jpg" alt="LED Light">
        <h3>Butterfly LED Light</h3>
        <p>BDT 129</p>
      </div>
    </div>

    <div class="contact">
      <h2>Contact Us</h2>
      <p><strong>Phone:</strong> +8801XXXXXXXXX</p>
      <p>Want to order or have questions? Call us anytime during business hours.</p>
      <a href="https://wa.me/8801XXXXXXXXX" class="whatsapp" target="_blank">Chat on WhatsApp</a>
    </div>

    <div class="map">
      <h2>Find Us on Google Maps</h2>
      <iframe src="https://maps.google.com/maps?q=23.7656964,90.3583257&z=17&output=embed" width="100%" height="300" frameborder="0" style="border:0" allowfullscreen></iframe>
    </div>
  </div>
  <footer>
    &copy; 2025 Cycle365. All rights reserved.
  </footer>
</body>
</html>

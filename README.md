<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Shop</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
    header { background-color: #2c3e50; color: white; padding: 20px; text-align: center; }
    nav a { color: white; margin: 0 10px; text-decoration: none; }
    .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; padding: 20px; }
    .product { border: 1px solid #ccc; padding: 10px; border-radius: 5px; text-align: center; }
    .product img { width: 100%; height: auto; border-radius: 5px; }
    .product h3 { margin: 10px 0 5px; }
    .product p { margin: 5px 0; }
    button { padding: 8px 12px; background: #27ae60; color: white; border: none; border-radius: 5px; }
    footer { background: #f4f4f4; padding: 10px; text-align: center; }
  </style>
</head>
<body>

<header>
  <h1>My Online Shop</h1>
  <nav>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="products" class="products">
  <div class="product">
    <img src="https://via.placeholder.com/200" alt="Product 1">
    <h3>Smart Watch</h3>
    <p>৳1500</p>
    <button>Add to Cart</button>
  </div>
  <div class="product">
    <img src="https://via.placeholder.com/200" alt="Product 2">
    <h3>Wireless Earbuds</h3>
    <p>৳1200</p>
    <button>Add to Cart</button>
  </div>
  <div class="product">
    <img src="https://via.placeholder.com/200" alt="Product 3">
    <h3>Bluetooth Speaker</h3>
    <p>৳1800</p>
    <button>Add to Cart</button>
  </div>
</section>

<section id="contact" style="padding: 20px;">
  <h2>Contact Us</h2>
  <p>Email: myshop@email.com</p>
  <p>Phone: 01812-345678</p>
</section>

<footer>
  <p>&copy; 2025 My Shop. All rights reserved.</p>
</footer>

</body>
</html>

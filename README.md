<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sports Brand</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="logo">SportsBrand</div>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#products">Products</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home">
    <h1>Welcome to SportsBrand</h1>
    <p>Quality gear for champions.</p>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>We provide premium sports equipment and apparel to help you perform at your best.</p>
  </section>

  <section id="products">
    <h2>Our Products</h2>
    <div class="product-grid">
      <div class="product">
        <img src="product1.jpg" alt="Product 1">
        <h3>Running Shoes</h3>
      </div>
      <div class="product">
        <img src="product2.jpg" alt="Product 2">
        <h3>Sportswear</h3>
      </div>
      <div class="product">
        <img src="product3.jpg" alt="Product 3">
        <h3>Accessories</h3>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2024 SportsBrand. All rights reserved.</p>
  </footer>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #333;
  color: white;
  padding: 1rem 2rem;
}

header .logo {
  font-size: 1.5rem;
  font-weight: bold;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 1rem;
}

nav ul li a {
  color: white;
  text-decoration: none;
}

section {
  padding: 2rem;
  text-align: center;
}

#home {
  background: url('hero.jpg') no-repeat center center/cover;
  color: white;
  padding: 4rem 2rem;
}

.product-grid {
  display: flex;
  gap: 1rem;
  justify-content: center;
}

.product {
  border: 1px solid #ddd;
  padding: 1rem;
  text-align: center;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 1rem 0;
}


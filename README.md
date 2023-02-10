<!DOCTYPE html>
<html>
  <head>
    <title>My Online Store</title>
    <link rel="stylesheet" type="text/css" href="style.css">
  </head>
  <body>
    <header>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#products">Products</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <section id="about">
        <h1>About Us</h1>
        <p>We are a team of passionate individuals dedicated to providing high-quality products to our customers. Our goal is to make shopping easy and convenient for everyone.</p>
      </section>

      <section id="products">
        <h1>Our Products</h1>
        <ul>
          <li>
            <h2>Product 1</h2>
            <img src="product1.jpg" alt="Product 1">
            <p>Description: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor justo vel velit bibendum, in rutrum justo condimentum.</p>
            <p>Price: $19.99</p>
            <button>Add to Cart</button>
          </li>

          <li>
            <h2>Product 2</h2>
            <img src="product2.jpg" alt="Product 2">
            <p>Description: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor justo vel velit bibendum, in rutrum justo condimentum.</p>
            <p>Price: $29.99</p>
            <button>Add to Cart</button>
          </li>

          <li>
            <h2>Product 3</h2>
            <img src="product3.jpg" alt="Product 3">
            <p>Description: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor justo vel velit bibendum, in rutrum justo condimentum.</p>
            <p>Price: $39.99</p>
            <button>Add to Cart</button>
          </li>
        </ul>
      </section>

      <section id="contact">
        <h1>Contact Us</h1>
        <form action="submit-form.php" method="post">
          <label for="name">Name:</label>
          <input type="text" id="name" name="name" required>

          <label for="email">Email:</label>
          <input type="email" id="email" name="email" required>

         

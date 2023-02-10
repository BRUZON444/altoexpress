<!DOCTYPE html>
<html>
  <head>
    <title>My First Website</title>
  </head>
  <body>
    <header>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <section id="about">
        <h1>About Us</h1>
        <p>We are a team of passionate individuals dedicated to providing high-quality services to our clients. Our goal is to help our clients achieve their goals and succeed in their ventures.</p>
      </section>

      <section id="services">
        <h1>Our Services</h1>
        <ul>
          <li>Web Design and Development</li>
          <li>Search Engine Optimization (SEO)</li>
          <li>Social Media Management</li>
        </ul>
      </section>

      <section id="contact">
        <h1>Contact Us</h1>
        <form action="submit-form.php" method="post">
          <label for="name">Name:</label>
          <input type="text" id="name" name="name" required>

          <label for="email">Email:</label>
          <input type="email" id="email" name="email" required>

          <label for="message">Message:</label>
          <textarea id="message" name="message" required></textarea>

          <input type="submit" value="Submit">
        </form>
      </section>
    </main>

    <footer>
      <p>Copyright © 2023 My First Website</p>
    </footer>
  </body>
</html>

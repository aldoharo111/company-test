# company-test
<!DOCTYPE html>
<html>
<head>
  <title>Website Company</title>
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home">
    <h1>Welcome to Website Company</h1>
    <p>We build beautiful and responsive websites for your business</p>
    <a href="#contact" class="btn">Get in touch</a>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li>Web Design</li>
      <li>Web Development</li>
      <li>Mobile App Development</li>
      <li>SEO Optimization</li>
    </ul>
  </section>

  <section id="portfolio">
    <h2>Our Portfolio</h2>
    <div class="portfolio-item">
      <img src="portfolio1.jpg" alt="Project 1">
      <h3>Project 1</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
    </div>
    <div class="portfolio-item">
      <img src="portfolio2.jpg" alt="Project 2">
      <h3>Project 2</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" name="name" placeholder="Your Name">
      <input type="email" name="email" placeholder="Your Email">
      <textarea name="message" placeholder="Your Message"></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2023 Website Company. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>

# Landing-page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Landing Page</title>
  <style>
    body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

.container {
  width: 80%;
  margin: 0 auto;
}

header {
  background-color: #333;
  color: #fff;
  padding: 20px 0;
}

header h1 {
  margin: 0;
}

nav ul {
  list-style-type: none;
  padding: 0;
}

nav ul li {
  display: inline;
  margin-right: 20px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
}

#hero {
  background-image: url('hero-bg.jpg');
  color: #fff;
  text-align: center;
  padding: 100px 0;
}

#about,
#features,
#contact {
  padding: 100px 0;
}

.btn {
  display: inline-block;
  padding: 10px 20px;
  background-color: #ff6600;
  color: #fff;
  text-decoration: none;
  border-radius: 5px;
}

section h2 {
  text-align: center;
}

footer {
  background-color: #333;
  color: #fff;
  padding: 20px 0;
  text-align: center;
}

footer ul {
  list-style-type: none;
  padding: 0;
}

footer ul li {
  display: inline;
  margin-right: 10px;
}

footer ul li a {
  color: #fff;
  text-decoration: none;
}

  </style>
</head>
<body>
  <header>
    <div class="container">
      <h1>Company Name</h1>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#features">Features</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section id="hero">
    <div class="container">
      <h2>Welcome to our Website</h2>
      <p>We provide amazing products and services that will make your life easier.</p>
      <a href="#contact" class="btn">Get Started</a>
    </div>
  </section>

  <section id="about">
    <div class="container">
      <h2>About Us</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum sagittis lacus eu suscipit.</p>
    </div>
  </section>

  <section id="features">
    <div class="container">
      <h2>Features</h2>
      <ul>
        <li>Feature 1</li>
        <li>Feature 2</li>
        <li>Feature 3</li>
      </ul>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h2>Contact Us</h2>
      <p>Get in touch with us to learn more about our products and services.</p>
      <form>
        <input type="text" placeholder="Name">
        <input type="email" placeholder="Email">
        <textarea placeholder="Message"></textarea>
        <button type="submit">Send</button>
      </form>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2024 Company Name. All rights reserved.</p>
      <ul>
        <li><a href="#">Privacy Policy</a></li>
        <li><a href="#">Terms of Service</a></li>
      </ul>
    </div>
  </footer>
</body>
</html>

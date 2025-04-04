<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Elevate English Institute</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      background-color: #f4f4f4;
    }

    header {
      background-color: #1a237e;
      color: white;
      padding: 1rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    .logo {
      display: flex;
      align-items: center;
    }

    .logo img {
      height: 50px;
      margin-right: 10px;
    }

    nav {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      background-color: #3949ab;
    }

    nav a {
      color: white;
      padding: 0.75rem 1.5rem;
      text-decoration: none;
      display: inline-block;
    }

    nav a:hover {
      background-color: #5c6bc0;
    }

    .hero {
      background: #7986cb;
      color: white;
      text-align: center;
      padding: 4rem 2rem;
    }

    .section {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
      background: white;
      margin-top: 1rem;
      border-radius: 8px;
    }

    form {
      display: grid;
      gap: 1rem;
    }

    input, textarea {
      padding: 0.75rem;
      font-size: 1rem;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    button {
      background-color: #1a237e;
      color: white;
      padding: 0.75rem;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-size: 1rem;
    }

    button:hover {
      background-color: #303f9f;
    }

    footer {
      text-align: center;
      background: #1a237e;
      color: white;
      padding: 1rem;
      margin-top: 2rem;
    }

    @media (max-width: 768px) {
      header, nav {
        flex-direction: column;
        text-align: center;
      }

      .logo img {
        margin-bottom: 10px;
      }
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">
      <img src="https://via.placeholder.com/50" alt="Elevate English Logo" />
      <h1>Elevate English Institute</h1>
    </div>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#courses">Courses</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <h2>Fluent. Confident. Global.</h2>
    <p>Join Elevate English Institute and transform your language skills today.</p>
  </section>

  <section id="about" class="section">
    <h2>About Us</h2>
    <p>At Elevate English Institute, we are committed to helping learners of all levels master the English language. Our certified instructors, engaging curriculum, and personalized attention ensure every student reaches their potential.</p>
  </section>

  <section id="courses" class="section">
    <h2>Our Courses</h2>
    <ul>
      <li>Beginner to Advanced English Programs</li>
      <li>IELTS & TOEFL Preparation</li>
      <li>Business English</li>
      <li>Spoken English Workshops</li>
    </ul>
  </section>

  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <form>
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
    <p style="margin-top: 1rem;">Or reach us at: contact@elevateenglish.com | +123 456 7890</p>
  </section>

  <footer>
    <p>&copy; 2025 Elevate English Institute. All rights reserved.</p>
  </footer>

</body>
</html>

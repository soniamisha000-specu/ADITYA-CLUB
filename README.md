<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Aditya Club Gym</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      background: #0f172a;
      color: white;
    }

    header {
      background: #020617;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      color: #38bdf8;
    }

    nav a {
      margin-left: 20px;
      color: #e5e7eb;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      padding: 80px 40px;
      text-align: center;
      background: linear-gradient(120deg, #38bdf8, #0ea5e9);
    }

    .hero h2 {
      font-size: 40px;
      margin-bottom: 15px;
    }

    .section {
      padding: 50px 40px;
    }

    .card {
      background: #020617;
      padding: 20px;
      border-radius: 12px;
      margin-top: 15px;
      box-shadow: 0 0 10px rgba(0,0,0,.4);
    }

    footer {
      margin-top: 30px;
      padding: 20px;
      text-align: center;
      background: #020617;
      color: #9ca3af;
    }

    .btn {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 18px;
      border-radius: 999px;
      background: #38bdf8;
      color: #020617;
      text-decoration: none;
      font-weight: bold;
    }
  </style>
</head>

<body>

  <header>
    <h1>Aditya Club</h1>

    <nav>
      <a href="#about">About</a>
      <a href="#plans">Plans</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Build Your Best Body</h2>
    <p>Professional trainers, modern equipment, and a motivating environment.</p>
    <a class="btn" href="#contact">Join Now</a>
  </section>

  <section id="about" class="section">
    <h2>About Aditya Club</h2>
    <div class="card">
      <p>
        Aditya Club is a premium gym designed to help you stay fit, focused, and healthy.
        We provide strength training, cardio workouts, personal coaching, and more.
      </p>
    </div>
  </section>

  <section id="plans" class="section">
    <h2>Membership Plans</h2>

    <div class="card">
      <strong>Basic Plan</strong>
      <p>Access to gym equipment</p>
    </div>

    <div class="card">
      <strong>Pro Plan</strong>
      <p>Gym + Personal Trainer + Diet Plan</p>
    </div>
  </section>

  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <div class="card">
      <p><strong>Phone:</strong> 7733034382</p>
      <p><strong>Address:</strong> Your Gym Address Here</p>
      <a class="btn" href="tel:7733034382">Call Now</a>
    </div>
  </section>

  <footer>
    © 2025 Aditya Club — Stay Strong 💪
  </footer>

</body>
</html>

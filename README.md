 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Sparklin Global Synergy</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: #222;
      background: #f5f7fa;
    }

    header {
      background: #071426;
      color: white;
      padding: 25px 20px;
      text-align: center;
    }

    header h1 {
      color: #00ff66;
      font-size: 28px;
      margin-bottom: 5px;
    }

    header p {
      font-size: 15px;
    }

    nav {
      background: #123b66;
      padding: 14px;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 10px;
      font-weight: bold;
    }

    nav a:hover {
      color: #00ff66;
    }

    .hero {
      background: white;
      text-align: center;
      padding: 60px 20px;
    }

    .hero h2 {
      color: #0b1f3a;
      font-size: 34px;
      margin-bottom: 15px;
    }

    .hero p {
      max-width: 700px;
      margin: auto;
      font-size: 17px;
    }

    .btn {
      display: inline-block;
      margin-top: 25px;
      padding: 13px 25px;
      background: #00b84d;
      color: white;
      text-decoration: none;
      border-radius: 6px;
      font-weight: bold;
    }

    .btn:hover {
      background: #008f3c;
    }

    section {
      padding: 50px 20px;
    }

    .container {
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      color: #0b1f3a;
      text-align: center;
      margin-bottom: 20px;
    }

    .about {
      background: #ffffff;
    }

    .mission-vision {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }

    .card {
      background: white;
      padding: 25px;
      border-radius: 10px;
      box-shadow: 0 3px 10px rgba(0,0,0,0.08);
    }

    .card h3 {
      color: #00a847;
      margin-bottom: 10px;
    }

    .services {
      background: #eaf0f5;
    }

    .service-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }

    .service {
      background: white;
      padding: 25px;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 3px 10px rgba(0,0,0,0.08);
    }

    .service h3 {
      color: #0b1f3a;
      margin-bottom: 10px;
    }

    .contact {
      text-align: center;
      background: #071426;
      color: white;
    }

    .contact h2 {
      color: #00ff66;
    }

    .contact p {
      margin: 10px 0;
    }

    .contact a {
      color: #00ff66;
      text-decoration: none;
      font-weight: bold;
    }

    footer {
      background: #020914;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>

<body>

  <header>
    <h1>Sparklin Global Synergy</h1>
    <p>Delivering Excellence Through Innovation and Strategic Partnerships</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About Us</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero" id="home">
    <div class="container">
      <h2>Welcome to Sparklin Global Synergy</h2>
      <p>
        We provide quality contract and service delivery solutions designed
        to enhance operational efficiency, maximize value, and support
        sustainable development.
      </p>

      <a href="#contact" class="btn">Contact Us</a>
    </div>
  </section>

  <section class="about" id="about">
    <div class="container">
      <h2>About Us</h2>

      <div class="mission-vision">

        <div class="card">
          <h3>Our Mission</h3>
          <p>
            Our mission is to enhance operational efficiency, maximize value,
            and contribute to sustainable development. To deliver superior
            quality services that meet the evolving needs of our clients through
            dedication, innovation, and strategic partnerships.
          </p>
        </div>

        <div class="card">
          <h3>Our Vision</h3>
          <p>
            To be the benchmark of excellence and innovation in providing
            contracts and service delivery solutions, driving progress and
            efficiency across industries.
          </p>
        </div>

      </div>
    </div>
  </section>

  <section class="services" id="services">
    <div class="container">
      <h2>Our Services</h2>

      <div class="service-grid">

        <div class="service">
          <h3>Contract Services</h3>
          <p>
            Professional contract solutions tailored to meet the needs of
            organizations and businesses.
          </p>
        </div>

        <div class="service">
          <h3>Service Delivery</h3>
          <p>
            Efficient and reliable service delivery focused on quality and
            customer satisfaction.
          </p>
        </div>

        <div class="service">
          <h3>Consulting</h3>
          <p>
            Strategic consulting services to help businesses improve
            operations and achieve their goals.
          </p>
        </div>

        <div class="service">
          <h3>Strategic Partnerships</h3>
          <p>
            Building strong partnerships that create value and support
            sustainable growth.
          </p>
        </div>

      </div>
    </div>
  </section>

  <section class="contact" id="contact">
    <div class="container">
      <h2>Contact Us</h2>

      <p>Get in touch with Sparklin Global Synergy today.</p>

      <p>
        Phone:
        <a href="tel:+2349023171830">+234 902 317 1830</a>
      </p>

      <p>
        WhatsApp:
        <a href="https://wa.me/2349023171830">Chat with us on WhatsApp</a>
      </p>

    </div>
  </section>

  <footer>
    <p>&copy; 2026 Sparklin Global Synergy. All Rights Reserved.</p>
  </footer>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Sammarth Trading & Projects | Official Website</title>
  <meta name="description" content="Welcome to Sammarth Trading & Projects, a group of companies with different departments working toward a shared vision.">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: #f5f7f0;
      color: #20251b;
      line-height: 1.7;
    }

    header {
      background: #fff;
      padding: 14px 6%;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
      flex-wrap: wrap;
      box-shadow: 0 2px 12px #00000012;
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 12px;
    }

    .brand img {
      width: 65px;
      height: 65px;
      object-fit: contain;
      border-radius: 50%;
    }

    .brand h2 {
      font-size: 18px;
      color: #526b20;
      line-height: 1.3;
    }

    .brand p {
      font-size: 12px;
      color: #555;
    }

    nav {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    nav a {
      text-decoration: none;
      color: #26331a;
      font-weight: bold;
    }

    nav a:hover {
      color: #78952c;
    }

    .hero {
      min-height: 78vh;
      padding: 65px 7%;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      background: linear-gradient(135deg, #263817, #617d29, #849a45);
      color: white;
    }

    .hero img {
      width: 190px;
      height: 190px;
      object-fit: contain;
      border-radius: 50%;
      margin-bottom: 25px;
      border: 5px solid #ffffff80;
    }

    .hero h1 {
      font-size: clamp(32px, 6vw, 58px);
      line-height: 1.2;
      margin-bottom: 18px;
    }

    .hero p {
      max-width: 750px;
      font-size: 18px;
      margin-bottom: 28px;
    }

    .button {
      display: inline-block;
      background: white;
      color: #3c511e;
      padding: 12px 26px;
      border-radius: 30px;
      font-weight: bold;
      text-decoration: none;
    }

    .button:hover {
      background: #e9efd9;
    }

    section {
      padding: 75px 7%;
      scroll-margin-top: 20px;
    }

    section h2 {
      text-align: center;
      font-size: 32px;
      color: #536d25;
      margin-bottom: 24px;
    }

    .intro {
      max-width: 850px;
      margin: auto;
      text-align: center;
    }

    .departments {
      background: #e9eedf;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 22px;
      margin-top: 35px;
    }

    .card {
      background: white;
      padding: 26px;
      border-radius: 12px;
      border-bottom: 4px solid #77933a;
      box-shadow: 0 5px 18px #0000000a;
    }

    .card h3 {
      color: #536d25;
      margin-bottom: 12px;
    }

    .vision {
      background: #293b1d;
      color: white;
      text-align: center;
    }

    .vision h2 {
      color: #d6e7a5;
    }

    .vision p {
      max-width: 800px;
      margin: auto;
    }

    footer {
      background: #172313;
      color: white;
      text-align: center;
      padding: 28px 7%;
    }

    footer p {
      margin: 4px 0;
    }

    @media (max-width: 650px) {
      header {
        justify-content: center;
      }

      nav {
        justify-content: center;
        gap: 14px;
      }

      .brand h2 {
        font-size: 16px;
      }

      .hero img {
        width: 150px;
        height: 150px;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="brand">
      <img src="logo.jpg" alt="Sammarth Trading & Projects logo">
      <div>
        <h2>SAMMARTH</h2>
        <p>Trading & Projects</p>
      </div>
    </div>

    <nav>
      <a href="#home">Home</a>
      <a href="#about">About Us</a>
      <a href="#departments">Departments</a>
      <a href="#vision">Our Vision</a>
    </nav>
  </header>

  <main>
    <section class="hero" id="home">
      <img src="logo.jpg" alt="Official Sammarth company logo">

      <h1>Sammarth Trading & Projects</h1>

      <p>
        A group of companies bringing different departments
        together to pursue opportunities, encourage innovation,
        and build a shared future.
      </p>

      <a href="#about" class="button">Discover Our Company</a>
    </section>

    <section id="about">
      <h2>About Sammarth</h2>

      <p class="intro">
        Sammarth Trading & Projects is a group of companies
        consisting of different departments. Our goal is to
        bring business activities and ideas together under
        one organization, encouraging collaboration, development,
        and new opportunities.
      </p>
    </section>

    <section class="departments" id="departments">
      <h2>Our Departments</h2>

      <p class="intro">
        Our departments represent different areas of work
        that can contribute to the growth and development
        of Sammarth Trading & Projects.
      </p>

      <div class="cards">
        <article class="card">
          <h3>Trading</h3>
          <p>
            Supporting trading activities and business
            opportunities.
          </p>
        </article>

        <article class="card">
          <h3>Projects</h3>
          <p>
            Supporting the planning and development
            of projects and new initiatives.
          </p>
        </article>

        <article class="card">
          <h3>Technology</h3>
          <p>
            Exploring technology and digital solutions
            that can support business activities.
          </p>
        </article>

        <article class="card">
          <h3>Business Development</h3>
          <p>
            Exploring opportunities for growth,
            partnerships, and future development.
          </p>
        </article>
      </div>
    </section>

    <section class="vision" id="vision">
      <h2>Our Vision</h2>

      <p>
        Our vision is to develop a connected group of companies
        where different departments work together, encourage
        innovation, and pursue meaningful opportunities for
        sustainable growth and a successful future.
      </p>
    </section>
  </main>

  <footer>
    <p><strong>SAMMARTH TRADING & PROJECTS</strong></p>
    <p>Building Opportunities. Developing Projects. Growing Together.</p>
    <p>&copy; <span id="year"></span> Sammarth Trading & Projects.</p>
  </footer>

  <script>
    document.getElementById("year").textContent =
      new Date().getFullYear();
  </script>

</body>
</html>

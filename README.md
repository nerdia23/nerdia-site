# nerdia-site
Jednoduchá firemná stránka pre NERDIA s.r.o.
    <!DOCTYPE html>
<html lang="sk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>NERDIA s.r.o. – Stavebné práce</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
    }
    header {
      background: #2e3a59;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #1d253b;
      text-align: center;
      padding: 10px 0;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1581091012184-7e0cdfbb6799') no-repeat center center/cover;
      color: white;
      padding: 80px 20px;
      text-align: center;
    }
    .hero h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 20px;
    }
    .section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
      background: white;
      margin-bottom: 20px;
    }
    .section h2 {
      color: #2e3a59;
    }
    footer {
      background: #2e3a59;
      color: white;
      text-align: center;
      padding: 15px;
    }
    .button {
      background: #ff9900;
      color: white;
      padding: 12px 24px;
      text-decoration: none;
      border-radius: 4px;
      font-weight: bold;
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
  </style>
</head>
<body>

<header>
  <h1>NERDIA s.r.o.</h1>
  <p>Stavebné práce – Elektrina, Voda, Rekonštrukcie na kľúč</p>
</header>

<nav>
  <a href="#">Domov</a>
  <a href="#sluzby">Služby</a>
  <a href="#kontakt">Kontakt</a>
</nav>

<section class="hero">
  <h1>Staviame spoľahlivo</h1>
  <p>Všetky stavebné práce: elektroinštalácie, vodoinštalácie, rekonštrukcie</p>
  <br />
  <a href="#kontakt" class="button">Získať ponuku</a>
</section>

<section class="section" id="sluzby">
  <h2>Naše služby</h2>
  <ul>
    <li>Kompletné stavebné práce</li>
    <li>Elektroinštalácie – bytové a priemyselné</li>
    <li>Vodoinštalácie a kúrenie</li>
    <li>Rekonštrukcie bytov, domov a objektov</li>
    <li>Stavby na kľúč</li>
  </ul>
</section>

<section class="section" id="kontakt">
  <h2>Kontaktujte nás</h2>
  <form action="https://formspree.io/f/yourFormID" method="POST">
    <label for="name">Meno:</label>
    <input type="text" id="name" name="name" required />

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required />

    <label for="message">Správa:</label>
    <textarea id="message" name="message" rows="5" required></textarea>

    <button type="submit" class="button">Odoslať správu</button>
  </form>
  <p>📞 Telefón: +421 908 681 227</p>
  <p>📧 Email: nerdia.sro@gmail.com</p>
  <p>📍 Slovensko</p>
</section>

<footer>
  &copy; 2025 NERDIA s.r.o. – Všetky práva vyhradené
</footer>

</body>
</html>
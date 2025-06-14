<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>VendezMieux</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      padding: 0;
      background: #ffffff;
      color: #222;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
      background: #f9f9f9;
      border-bottom: 1px solid #e0e0e0;
    }
    header h1 {
      font-weight: 800;
      color: #00b36b;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #222;
      font-weight: 600;
    }
    .hero {
      padding: 80px 20px;
      text-align: center;
    }
    .hero h2 {
      font-size: 36px;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 18px;
      margin-bottom: 30px;
    }
    .buttons a {
      display: inline-block;
      margin: 10px;
      padding: 15px 30px;
      font-size: 16px;
      font-weight: 600;
      border-radius: 8px;
      text-decoration: none;
    }
    .btn-blue { background: #007bff; color: white; }
    .btn-green { background: #00b36b; color: white; }
    .section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: 0 auto;
    }
    .section h3 {
      font-size: 24px;
      margin-bottom: 20px;
      text-align: center;
    }
    .features {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
    }
    .feature {
      width: 250px;
      margin: 20px;
      text-align: center;
    }
    footer {
      background: #f0f0f0;
      padding: 30px;
      text-align: center;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <header>
    <h1>VendezMieux</h1>
    <nav>
      <a href="#">Accueil</a>
      <a href="#">Trouver un bien</a>
      <a href="#">Vendre un bien</a>
      <a href="#">Tarifs</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Vendez mieux. Grâce à l’intelligence artificielle.</h2>
    <p>Gagnez du temps, vendez plus vite et plus intelligemment. Notre IA connecte les bons vendeurs aux bons acheteurs en quelques clics.</p>
    <div class="buttons">
      <a href="#" class="btn-blue">Je cherche un bien</a>
      <a href="#" class="btn-green">Je veux vendre</a>
    </div>
  </section>

  <section class="section">
    <h3>Comment ça marche ?</h3>
    <div class="features">
      <div class="feature">
        <h4>📋 Vous décrivez vos besoins</h4>
        <p>Remplissez un formulaire intelligent en 2 minutes.</p>
      </div>
      <div class="feature">
        <h4>🤖 L’IA recommande les meilleures options</h4>
        <p>Biens ou agents adaptés à votre situation.</p>
      </div>
      <div class="feature">
        <h4>🤝 Vous entrez en contact</h4>
        <p>Visitez, signez, vendez.</p>
      </div>
    </div>
  </section>

  <section class="section">
    <h3>Vous êtes un vendeur ou un agent immobilier ?</h3>
    <div class="features">
      <div class="feature">
        <p>✅ Créez une annonce automatiquement grâce à l’IA</p>
        <p>✅ Générez des leads qualifiés</p>
        <p>✅ Gagnez du temps, optimisez vos chances</p>
      </div>
    </div>
  </section>

  <section class="section">
    <h3>Pourquoi VendezMieux ?</h3>
    <div class="features">
      <div class="feature">
        <p>✅ IA de matching ultra précise</p>
      </div>
      <div class="feature">
        <p>✅ Optimisation du rendement locatif</p>
      </div>
      <div class="feature">
        <p>✅ Assistance intelligente 24h/24</p>
      </div>
      <div class="feature">
        <p>✅ Zéro frais cachés, commission transparente</p>
      </div>
    </div>
  </section>

  <footer>
    © 2025 VendezMieux – Tous droits réservés | Contact | Mentions légales
  </footer>
</body>
</html>

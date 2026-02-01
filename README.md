<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ManCoiffure – Salon de coiffure</title>
  <meta name="description" content="ManCoiffure – Salon de coiffure moderne. Coupes homme, femme, enfant. Prenez rendez-vous." />
  <style>
    body { margin:0; font-family: Arial, sans-serif; background:#111; color:#fff; }
    header { padding:60px 20px; text-align:center; background:#000; }
    header h1 { font-size:3em; margin:0; }
    header p { color:#ccc; }
    section { padding:60px 20px; max-width:1000px; margin:auto; }

    /* TITRES */
    h2.section-title {
      font-size:2.5em;
      font-weight:bold;
      text-decoration: underline;
      text-align:center;
      margin-bottom:40px;
    }

    /* CARTES */
    .services { 
      display:grid; 
      grid-template-columns:repeat(auto-fit,minmax(260px,1fr)); 
      gap:25px; 
    }

    .card { 
      background:#1c1c1c; 
      padding:30px; 
      border-radius:15px; 
      font-size:1.2em;
      text-align:center;
    }

    footer { background:#000; padding:30px; text-align:center; color:#777; }
    a.button { display:inline-block; margin-top:20px; padding:15px 30px; background:#c49b63; color:#000; text-decoration:none; border-radius:30px; }
  </style>
</head>
<body>

<header>
  <h1>ManCoiffure</h1>
  <p>Chez MANCOIFFURE, le style qui vous ressemble.</p>
  <a class="button" href="#contact">Prendre rendez-vous</a>
</header>

<section>
  <h2 class="section-title">Prix et Services</h2>
  <div class="services">
    <div class="card">✂️ <strong>Coupe + Shampoing</strong><br>15€</div>
    <div class="card">👦 <strong>Coupe enfant (-12 ans)</strong><br>13€</div>
    <div class="card">🧔 <strong>Coupe + Barbe</strong><br>20€</div>
    <div class="card">🪒 <strong>Barbe</strong><br>10€</div>
    <div class="card">💈 <strong>Défrisage</strong><br>18€</div>
    <div class="card">⭐ <strong>Coupe + Barbe + Épilation</strong><br>25€</div>
  </div>
</section>

<section>
  <h2>.....................<br>..........................<br>..........................</h2>
</section>

<section id="contact">
  <h2 class="section-title">Contact</h2>
  <div class="card">
    <p>📍 Adresse : 14 Bd du Général de Gaulle 83780 Flayosc</p>
    <p>📞 Téléphone : 07 66 96 39 80</p>
    <p>🕒 Horaires : Lundi au dimanche de 9h–19h sauf mardi (fermé)</p>
  </div>
</section>

<footer>
  <p>© 2026 ManCoiffure – Tous droits réservés</p>
</footer>

</body>
</html>

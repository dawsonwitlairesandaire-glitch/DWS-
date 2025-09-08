<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DWS♤TOP UP - Recharges Free Fire</title>
<style>
  body {
    margin: 0;
    font-family: Arial, sans-serif;
    color: #fff;
    background: linear-gradient(270deg, #0f172a, #000, #1e3a8a);
    background-size: 600% 600%;
    animation: gradientBG 20s ease infinite;
    text-align: center;
    padding: 20px;
  }
  @keyframes gradientBG {
    0%{background-position:0% 50%;}
    50%{background-position:100% 50%;}
    100%{background-position:0% 50%;}
  }
  h1 { font-size: 3em; margin-bottom: 0.2em; text-shadow: 2px 2px 8px #000; }
  p.subtitle { font-size: 1.2em; margin-bottom: 30px; }

  /* Formulaire ID */
  .id-form {
    margin: 20px auto;
    max-width: 400px;
    background: rgba(255,255,255,0.05);
    padding: 15px;
    border-radius: 12px;
  }
  .id-form input {
    width: 90%;
    padding: 12px;
    border-radius: 8px;
    border: none;
    outline: none;
    font-size: 1em;
    text-align: center;
  }

  /* Packs container */
  .packs-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
  }
  .diamond-pack {
    flex: 1 1 200px;
    max-width: 220px;
    margin: 10px;
    padding: 25px;
    background: rgba(255,255,255,0.05);
    border-radius: 20px;
    transition: transform 0.3s, background 0.3s;
    box-shadow: 0 0 15px rgba(255,255,255,0.1);
    position: relative;
    overflow: hidden;
  }
  .diamond-pack:hover { transform: scale(1.08); background: rgba(255,255,255,0.15); box-shadow: 0 0 25px rgba(0,200,255,0.6); }

  .diamond-icon { font-size: 2em; animation: bounce 1.5s infinite; display: block; margin-bottom: 10px; }
  @keyframes bounce { 0%,100% {transform: translateY(0);} 50% {transform: translateY(-10px);} }

  .pack-title { font-size: 1.3em; margin-bottom: 10px; }
  .price { font-size: 0.9em; color: #00e0ff; margin-bottom: 15px; display: block; }

  .site-link {
    display: inline-block;
    padding: 12px 20px;
    background: linear-gradient(90deg, #ff3c00, #ff7300);
    color: #fff;
    font-weight: bold;
    text-decoration: none;
    border-radius: 12px;
    transition: background 0.3s, transform 0.2s;
    animation: pulse 2s infinite;
  }
  .site-link:hover { transform: scale(1.05); }
  @keyframes pulse { 0%, 100% { transform: scale(1);} 50% { transform: scale(1.05);} }

  .legal-note { font-size: 14px; color: #ccc; margin-top: 25px; }

  /* FAQ */
  .faq {
    max-width: 800px;
    margin: 40px auto;
    padding: 20px;
    text-align: left;
    background: rgba(255,255,255,0.05);
    border-radius: 15px;
    box-shadow: 0 0 15px rgba(0,0,0,0.3);
  }
  .faq h2 {
    text-align: center;
    margin-bottom: 20px;
    color: #00e0ff;
  }
  .faq-item { margin-bottom: 20px; }
  .faq-item h3 { margin-bottom: 8px; color: #ff7300; }
  .faq-item p { margin: 0; color: #ddd; line-height: 1.5em; }

  /* WhatsApp floating button */
  .whatsapp-float {
    position: fixed;
    width: 60px;
    height: 60px;
    bottom: 20px;
    right: 20px;
    background: #25d366;
    color: white;
    border-radius: 50%;
    text-align: center;
    font-size: 28px;
    line-height: 60px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.3);
    z-index: 100;
    transition: transform 0.3s;
  }
  .whatsapp-float:hover { transform: scale(1.1); background: #1ebe5d; }
</style>
</head>
<body>

<h1>DWS♤TOP UP</h1>
<p class="subtitle">Recharge tes diamants Free Fire facilement et légalement avec MonCash !</p>

<!-- Formulaire ID -->
<div class="id-form">
  <h2>🔑 Entrez votre ID Free Fire</h2>
  <input type="text" id="ffid" placeholder="Ex: 123456789" required>
</div>

<!-- Packs -->
<div class="packs-container">
  <div class="diamond-pack">
    <span class="diamond-icon">💎</span>
    <div class="pack-title">100 Diamants</div>
    <span class="price">500 HTG</span>
    <a href="#" class="site-link" onclick="sendOrder(500,'100 Diamants')">Payer avec MonCash</a>
  </div>

  <div class="diamond-pack">
    <span class="diamond-icon">💎</span>
    <div class="pack-title">230 Diamants</div>
    <span class="price">1000 HTG</span>
    <a href="#" class="site-link" onclick="sendOrder(1000,'230 Diamants')">Payer avec MonCash</a>
  </div>

  <div class="diamond-pack">
    <span class="diamond-icon">💎</span>
    <div class="pack-title">310 Diamants</div>
    <span class="price">1200 HTG</span>
    <a href="#" class="site-link" onclick="sendOrder(1200,'310 Diamants')">Payer avec MonCash</a>
  </div>

  <div class="diamond-pack">
    <span class="diamond-icon">💎</span>
    <div class="pack-title">520 Diamants</div>
    <span class="price">2000 HTG</span>
    <a href="#" class="site-link" onclick="sendOrder(2000,'520 Diamants')">Payer avec MonCash</a>
  </div>

  <div class="diamond-pack">
    <span class="diamond-icon">💎</span>
    <div class="pack-title">741 Diamants</div>
    <span class="price">2300 HTG</span>
    <a href="#" class="site-link" onclick="sendOrder(2300,'741 Diamants')">Payer avec MonCash</a>
  </div>

  <div class="diamond-pack">
    <span class="diamond-icon">💎</span>
    <div class="pack-title">880 Diamants</div>
    <span class="price">2800 HTG</span>
    <a href="#" class="site-link" onclick="sendOrder(2800,'880 Diamants')">Payer avec MonCash</a>
  </div>

  <div class="diamond-pack">
    <span class="diamond-icon">💎</span>
    <div class="pack-title">1023 Diamants</div>
    <span class="price">3500 HTG</span>
    <a href="#" class="site-link" onclick="sendOrder(3500,'1023 Diamants')">Payer avec MonCash</a>
  </div>

  <div class="diamond-pack">
    <span class="diamond-icon">💎</span>
    <div class="pack-title">3200 Diamants</div>
    <span class="price">10000 HTG</span>
    <a href="#" class="site-link" onclick="sendOrder(10000,'3200 Diamants')">Payer avec MonCash</a>
  </div>

  <div class="diamond-pack">
    <span class="diamond-icon">💎</span>
    <div class="pack-title">5500 Diamants</div>
    <span class="price">16000 HTG</span>
    <a href="#" class="site-link" onclick="sendOrder(16000,'5500 Diamants')">Payer avec MonCash</a>
  </div>
</div>

<!-- Mention légale -->
<p class="legal-note">
Toutes les recharges sont effectuées via MonCash officiel.<br>
DWS♤TOP UP ne collecte ni ne stocke vos informations de paiement. Site 100% légal et sécurisé.
</p>

<!-- FAQ -->
<div class="faq">
  <h2>❓ FAQ - Questions fréquentes</h2>

  <div class="faq-item">
    <h3>⏱️ Combien de temps prend la livraison des diamants ?</h3>
    <p>La livraison est généralement instantanée après confirmation du paiement. Dans certains cas, cela peut prendre jusqu'à 10 minutes.</p>
  </div>

  <div class="faq-item">
    <h3>💳 Est-ce que les paiements sont sécurisés ?</h3>
    <p>Oui ✅ Tous les paiements passent uniquement par la plateforme officielle <strong>MonCash</strong>. Nous ne stockons aucune donnée bancaire.</p>
  </div>

  <div class="faq-item">
    <h3>📱 Comment recharger mes diamants ?</h3>
    <p>Entre ton ID Free Fire, choisis ton pack, clique sur "Payer avec MonCash", puis suis les instructions. Tes diamants seront ajoutés à ton compte.</p>
  </div>

  <div class="faq-item">
    <h3>📞 Comment vous contacter en cas de problème ?</h3>
    <p>Tu peux nous écrire directement sur WhatsApp en cliquant sur le bouton en bas à droite.</p>
  </div>
</div>

<!-- Bouton WhatsApp flottant -->
<a href="https://wa.me/50938188312" class="whatsapp-float" target="_blank" rel="noopener noreferrer">💬</a>

<script>
function sendOrder(amount, pack) {
  let ffid = document.getElementById("ffid").value;
  if (ffid === "") {
    alert("⚠️ Merci d’entrer votre ID Free Fire avant de continuer !");
    return;
  }
  // lien MonCash
  let moncashLink = "https://www.moncashhaiti.com/paiement?merchant_id=38188312&amount=" + amount;
  // lien WhatsApp avec ID + pack
  let whatsappLink = "https://wa.me/50938188312?text=Nouvel%20TopUp%20:%0A👤%20ID%20Free%20Fire%20:%20" + ffid + "%0A💎%20Pack%20:%20" + pack + "%0A💰%20Montant%20:%20" + amount + "%20HTG";
  
  // ouvre MonCash et WhatsApp
  window.open(moncashLink, "_blank");
  window.open(whatsappLink, "_blank");
}
</script>

</body>
</html>

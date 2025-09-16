# Money-invest
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Money Invest</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Money Invest</h1>
    <p>Investir simplement et suivre vos gains en toute sécurité.</p>
  </header>

  <section class="features">
    <h2>Fonctionnalités</h2>
    <div class="feature-list">
      <div class="feature">
        <h3>Investissement simplifié</h3>
        <p>Placez de petits ou gros montants dans des portefeuilles diversifiés.</p>
      </div>
      <div class="feature">
        <h3>Suivi en temps réel</h3>
        <p>Tableau de bord clair avec alertes et performances.</p>
      </div>
      <div class="feature">
        <h3>Portefeuilles personnalisés</h3>
        <p>Choisissez ou suivez des stratégies adaptées à votre profil.</p>
      </div>
    </div>
  </section>

  <section class="pricing">
    <h2>Tarifs</h2>
    <div class="plans">
      <div class="plan">
        <h3>Starter</h3>
        <p>À partir de 50 €</p>
        <ul>
          <li>Portefeuilles de base</li>
          <li>Tableau de bord simple</li>
          <li>Support email</li>
        </ul>
        <p class="price">0,5 % / an</p>
      </div>
      <div class="plan">
        <h3>Croissance</h3>
        <p>À partir de 500 €</p>
        <ul>
          <li>Toutes les stratégies</li>
          <li>Alertes personnalisées</li>
          <li>Support chat + email</li>
        </ul>
        <p class="price">0,8 % / an</p>
      </div>
      <div class="plan">
        <h3>Premium</h3>
        <p>À partir de 5 000 €</p>
        <ul>
          <li>Stratégies avancées</li>
          <li>API trading</li>
          <li>Gestionnaire dédié</li>
        </ul>
        <p class="price">1 % / an</p>
      </div>
    </div>
  </section>

  <section class="kyc">
    <h2>Complétez vos informations</h2>
    <form id="kycForm">
      <label>Nom complet:<br><input type="text" name="nom" required></label><br>
      <label>Date de naissance:<br><input type="date" name="dob" required></label><br>
      <label>Adresse:<br><input type="text" name="adresse" required></label><br>
      <label>Email:<br><input type="email" name="email" required></label><br>
      <label>Téléphone:<br><input type="tel" name="tel" required></label><br>
      <label>Profil investisseur:<br>
        <select name="profil" required>
          <option value="">Choisir</option>
          <option value="conservateur">Conservateur</option>
          <option value="equilibre">Équilibré</option>
          <option value="dynamique">Dynamique</option>
        </select>
      </label><br><br>
      <button type="submit">Valider</button>
    </form>
  </section>

  <script src="script.js"></script>
</body>
</html>

<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Optimisez Votre Patrimoine</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
    }
    header {
      background: linear-gradient(135deg, #1e3a8a, #4f46e5);
      color: white;
      text-align: center;
      padding: 40px 20px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
    header h1 {
      margin: 0;
      font-size: 3em;
      animation: fadeIn 2s;
    }
    header p {
      font-size: 1.2em;
      animation: fadeIn 2.5s;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    .container {
      max-width: 1200px;
      margin: 20px auto;
      padding: 20px;
      background: white;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      border-radius: 8px;
    }
    .features {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: space-between;
      margin: 20px 0;
    }
    .feature {
      flex: 1;
      min-width: 250px;
      background: #e0e7ff;
      border-radius: 8px;
      padding: 20px;
      text-align: center;
      transition: transform 0.3s;
    }
    .feature:hover {
      transform: scale(1.05);
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
    }
    .feature h3 {
      color: #1e3a8a;
      margin-bottom: 10px;
    }
    .cta {
      text-align: center;
      margin: 30px 0;
    }
    .cta form input,
    .cta form select,
    .cta form textarea,
    .cta form button {
      padding: 10px;
      margin: 10px 0;
      border-radius: 5px;
      border: 1px solid #ddd;
      width: 90%;
      max-width: 500px;
      display: block;
      margin-left: auto;
      margin-right: auto;
    }
    .cta form button {
      background-color: #4f46e5;
      color: white;
      border: none;
      cursor: pointer;
      transition: background-color 0.3s;
    }
    .cta form button:hover {
      background-color: #3b82f6;
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: #1e3a8a;
      color: white;
      margin-top: 20px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Investissez dans Votre Avenir</h1>
    <p>Solutions en immobilier, SCPI et restructuration financière.</p>
  </header>

  <div class="container">
    <section class="features">
      <div class="feature">
        <h3>Immobilier</h3>
        <p>Des solutions sur mesure pour vos projets immobiliers.</p>
      </div>
      <div class="feature">
        <h3>SCPI</h3>
        <p>Investissez intelligemment pour générer des revenus passifs.</p>
      </div>
      <div class="feature">
        <h3>Restructuration</h3>
        <p>Réduisez vos mensualités et optimisez votre budget.</p>
      </div>
    </section>

    <section class="cta">
      <h2>Demandez une Simulation Personnalisée</h2>
      <form>
        <input type="text" placeholder="Nom et Prénom" required>
        <input type="email" placeholder="Adresse e-mail" required>
        <input type="tel" placeholder="Numéro de téléphone" required>
        <select required>
          <option value="" disabled selected>Choisissez une solution</option>
          <option value="immobilier">Financement Immobilier</option>
          <option value="scpi">Investissement SCPI</option>
          <option value="restructuration">Restructuration de Prêt</option>
        </select>
        <select required>
          <option value="" disabled selected>Situation Matrimoniale</option>
          <option value="celibataire">Célibataire</option>
          <option value="marie">Marié(e)</option>
          <option value="divorce">Divorcé(e)</option>
          <option value="veuf">Veuf/Veuve</option>
        </select>
        <input type="number" placeholder="Montant du financement (€)" required>
        <select required>
          <option value="" disabled selected>Type de Client</option>
          <option value="physique">Personne Physique</option>
          <option value="morale">Personne Morale</option>
        </select>
        <textarea placeholder="Décrivez brièvement votre projet" rows="4"></textarea>
        <input type="date" placeholder="Date souhaitée pour l'appel" required>
        <button type="submit">Envoyer ma Demande</button>
      </form>
    </section>
  </div>

  <footer>
    <p>© 2025 Votre Nom | Tous droits réservés</p>
  </footer>
</body>
</html>

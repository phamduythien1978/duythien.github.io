[Mise en route_Economie collaborative.html](https://github.com/user-attachments/files/23512348/Mise.en.route_Economie.collaborative.html)
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Préparation à l'écoute - Économie collaborative</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      line-height: 1.6;
      background-color: #f7f7f7;
      color: #222;
    }
    h1, h2, h3 {
      text-align: center;
    }
    .container {
      max-width: 1000px;
      margin: 0 auto 30px auto;
      background-color: #ffffff;
      padding: 20px 25px;
      border-radius: 6px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.08);
    }
    .section-title {
      font-weight: bold;
      font-size: 1.1em;
      margin-bottom: 8px;
      color: #0b4f8a;
    }
    .question-block {
      margin-bottom: 12px;
    }
    textarea {
      width: 100%;
      min-height: 60px;
      border-radius: 4px;
      border: 1px solid #ccc;
      padding: 6px;
      font-family: inherit;
      resize: vertical;
    }
    .lexique-table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 8px;
    }
    .lexique-table th, .lexique-table td {
      border: 1px solid #ddd;
      padding: 8px;
      vertical-align: top;
    }
    .lexique-table th {
      background-color: #f0f4f8;
    }
    select {
      padding: 4px;
      border-radius: 4px;
      border: 1px solid #bbb;
    }
    .affirmation-row {
      display: flex;
      align-items: center;
      gap: 10px;
      margin-bottom: 6px;
    }
    .affirmation-row span {
      flex: 1;
    }
    .timer-box {
      text-align: center;
      margin: 10px 0 18px 0;
      padding: 10px;
      border-radius: 6px;
      background-color: #eef5ff;
      border: 1px solid #c9dcff;
    }
    .timer-label {
      font-weight: bold;
      display: block;
      margin-bottom: 4px;
    }
    #timer {
      font-size: 1.4em;
      font-weight: bold;
    }
    button {
      padding: 8px 14px;
      font-size: 0.95em;
      border-radius: 4px;
      border: none;
      cursor: pointer;
      margin-top: 10px;
      margin-right: 8px;
    }
    #startTimerBtn {
      background-color: #0b4f8a;
      color: #fff;
    }
    .btn-check {
      background-color: #0b8a4a;
      color: #fff;
    }
    .btn-reset {
      background-color: #888;
      color: #fff;
    }
    .feedback {
      margin-top: 6px;
      font-size: 0.9em;
    }
    .correct {
      color: #1b8a3a;
      font-weight: bold;
    }
    .incorrect {
      color: #c0392b;
      font-weight: bold;
    }
    .note {
      font-size: 0.85em;
      color: #666;
      margin-top: 4px;
    }
  </style>
</head>
<body>

<h1>Activité de sensibilisation</h1>
<h2>Avant l'écoute : Comment encadrer l'économie collaborative ?</h2>

<div class="container">
  <div class="timer-box">
    <span class="timer-label">Minuteur de préparation avant l'écoute (suggestion : 10 minutes)</span>
    <div id="timer">10:00</div>
    <button id="startTimerBtn">Lancer le minuteur</button>
    <button id="resetTimerBtn" class="btn-reset">Réinitialiser</button>
    <div class="note">Pendant ce temps, complétez les activités ci-dessous avant de passer au document sonore et au QCM.</div>
  </div>
</div>

<div class="container">
  <div class="section-title">Étape 1. Mise en contexte</div>
  <p><strong>Consigne :</strong> À partir du titre <em>« Comment encadrer l’économie collaborative ? »</em>, répondez aux questions ci-dessous.</p>

  <div class="question-block">
    <p>1. Que signifie pour vous <strong>l’économie collaborative</strong> ? Donnez votre propre définition.</p>
    <textarea placeholder="Écrivez ici votre définition..."></textarea>
  </div>

  <div class="question-block">
    <p>2. Citez des exemples de plateformes ou d’activités collaboratives que vous connaissez.</p>
    <textarea placeholder="Exemples : covoiturage, location, services entre particuliers..."></textarea>
  </div>

  <div class="question-block">
    <p>3. Pourquoi, selon vous, certains pensent qu’il faut « encadrer » cette économie ?</p>
    <textarea placeholder="Notez vos hypothèses sur les enjeux, les risques, les questions de loi ou de fiscalité..."></textarea>
  </div>
</div>

<div class="container">
  <div class="section-title">Étape 2. Lexique de découverte</div>
  <p><strong>Consigne :</strong> Associez chaque mot à la définition qui convient en sélectionnant une lettre (a, b, c, d ou e).</p>

  <table class="lexique-table">
    <tr>
      <th>Mot / expression</th>
      <th>Votre choix</th>
      <th>Définitions</th>
    </tr>
    <tr>
      <td>1. une plateforme numérique</td>
      <td>
        <select id="lex1">
          <option value="">--</option>
          <option value="a">a</option>
          <option value="b">b</option>
          <option value="c">c</option>
          <option value="d">d</option>
          <option value="e">e</option>
        </select>
      </td>
      <td rowspan="5">
        <strong>a.</strong> Ensemble de lois ou règles qui encadrent une activité économique.<br>
        <strong>b.</strong> Entreprise ou site qui met en relation des particuliers pour échanger des biens ou services.<br>
        <strong>c.</strong> Activité dont l’objectif principal est de générer des bénéfices financiers.<br>
        <strong>d.</strong> Ensemble des règles relatives aux impôts et aux revenus.<br>
        <strong>e.</strong> Service proposé directement entre individus, sans passer par une entreprise traditionnelle.
      </td>
    </tr>
    <tr>
      <td>2. un service entre particuliers</td>
      <td>
        <select id="lex2">
          <option value="">--</option>
          <option value="a">a</option>
          <option value="b">b</option>
          <option value="c">c</option>
          <option value="d">d</option>
          <option value="e">e</option>
        </select>
      </td>
    </tr>
    <tr>
      <td>3. un cadre fiscal</td>
      <td>
        <select id="lex3">
          <option value="">--</option>
          <option value="a">a</option>
          <option value="b">b</option>
          <option value="c">c</option>
          <option value="d">d</option>
          <option value="e">e</option>
        </select>
      </td>
    </tr>
    <tr>
      <td>4. une activité lucrative</td>
      <td>
        <select id="lex4">
          <option value="">--</option>
          <option value="a">a</option>
          <option value="b">b</option>
          <option value="c">c</option>
          <option value="d">d</option>
          <option value="e">e</option>
        </select>
      </td>
    </tr>
    <tr>
      <td>5. une réglementation</td>
      <td>
        <select id="lex5">
          <option value="">--</option>
          <option value="a">a</option>
          <option value="b">b</option>
          <option value="c">c</option>
          <option value="d">d</option>
          <option value="e">e</option>
        </select>
      </td>
    </tr>
  </table>

  <button class="btn-check" onclick="checkLexique()">Vérifier le lexique</button>
  <button class="btn-reset" onclick="resetLexique()">Réinitialiser</button>
  <div id="lexiqueFeedback" class="feedback"></div>
</div>

<div class="container">
  <div class="section-title">Étape 3. Anticipation guidée</div>
  <p><strong>Consigne :</strong> Cochez les affirmations que vous pensez vraies <em>avant</em> l’écoute. Ensuite, après l’écoute, vous pourrez vérifier.</p>

  <div id="anticipation">
    <div class="affirmation-row">
      <input type="checkbox" id="a1">
      <span>a) L’économie collaborative échappe souvent aux règles fiscales traditionnelles.</span>
    </div>
    <div class="affirmation-row">
      <input type="checkbox" id="a2">
      <span>b) Les acteurs politiques cherchent uniquement à créer de nouveaux impôts.</span>
    </div>
    <div class="affirmation-row">
      <input type="checkbox" id="a3">
      <span>c) Certains particuliers utilisent ces plateformes comme une véritable source de revenus.</span>
    </div>
    <div class="affirmation-row">
      <input type="checkbox" id="a4">
      <span>d) Tous les travailleurs de ces plateformes sont déjà protégés comme des salariés.</span>
    </div>
    <div class="affirmation-row">
      <input type="checkbox" id="a5">
      <span>e) L’économie collaborative pose des questions de justice sociale et de concurrence.</span>
    </div>
  </div>

  <button class="btn-check" onclick="showAnticipationKey()">Afficher la correction (à utiliser après l'écoute)</button>
  <div id="anticipationFeedback" class="feedback note"></div>
</div>

<script>
  // Minuteur 10 minutes
  let timerInterval = null;
  let remainingSeconds = 600;

  function updateTimerDisplay() {
    const minutes = String(Math.floor(remainingSeconds / 60)).padStart(2, '0');
    const seconds = String(remainingSeconds % 60).padStart(2, '0');
    document.getElementById('timer').textContent = minutes + ":" + seconds;
  }

  document.getElementById('startTimerBtn').addEventListener('click', function() {
    if (timerInterval) return;
    timerInterval = setInterval(function() {
      if (remainingSeconds > 0) {
        remainingSeconds--;
        updateTimerDisplay();
      } else {
        clearInterval(timerInterval);
        timerInterval = null;
        alert("Temps de préparation terminé. Vous pouvez passer à l'écoute du document.");
      }
    }, 1000);
  });

  document.getElementById('resetTimerBtn').addEventListener('click', function() {
    clearInterval(timerInterval);
    timerInterval = null;
    remainingSeconds = 600;
    updateTimerDisplay();
  });

  updateTimerDisplay();

  // Correction lexique
  function checkLexique() {
    const answers = { lex1: 'b', lex2: 'e', lex3: 'd', lex4: 'c', lex5: 'a' };
    let correctCount = 0;
    let total = Object.keys(answers).length;

    for (let id in answers) {
      const select = document.getElementById(id);
      if (!select) continue;
      if (select.value === answers[id]) {
        correctCount++;
        select.style.borderColor = '#1b8a3a';
      } else {
        select.style.borderColor = '#c0392b';
      }
    }

    const fb = document.getElementById('lexiqueFeedback');
    if (correctCount === total) {
      fb.innerHTML = "<span class='correct'>Parfait :</span> toutes les associations sont correctes.";
    } else {
      fb.innerHTML = "<span class='incorrect'>Résultat :</span> " + correctCount + " / " + total +
        " correctes. Corrigez les items en rouge.";
    }
  }

  function resetLexique() {
    const ids = ['lex1', 'lex2', 'lex3', 'lex4', 'lex5'];
    ids.forEach(id => {
      const s = document.getElementById(id);
      if (s) {
        s.value = "";
        s.style.borderColor = '#bbb';
      }
    });
    document.getElementById('lexiqueFeedback').innerHTML = "";
  }

  // Anticipation - clé (à consulter après l'écoute)
  function showAnticipationKey() {
    const fb = document.getElementById('anticipationFeedback');
    fb.innerHTML =
      "<strong>Clé (à vérifier après l'écoute) :</strong><br>" +
      "a) Vrai – le reportage évoque des zones grises fiscales.<br>" +
      "b) Faux – l'objectif principal n'est pas seulement de créer un impôt, mais de définir un cadre.<br>" +
      "c) Vrai – certains tirent des revenus importants via ces plateformes.<br>" +
      "d) Faux – la question de l'absence de protection sociale est soulevée.<br>" +
      "e) Vrai – l'émission interroge les enjeux de justice sociale, de concurrence et de régulation.";
  }
</script>

</body>
</html>

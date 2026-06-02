<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Monsieur Mi — Conditions d'accès</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            background: linear-gradient(135deg, #1e1a1f 0%, #2a2429 100%);
            font-family: 'Inter', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 2rem;
        }
        .card {
            max-width: 950px;
            width: 100%;
            background: rgba(25, 20, 23, 0.88);
            backdrop-filter: blur(2px);
            border-radius: 2rem;
            padding: 2rem 2rem;
            box-shadow: 0 25px 45px rgba(0, 0, 0, 0.4), 0 0 0 1px rgba(230, 200, 180, 0.1);
            border: 1px solid rgba(210, 180, 140, 0.25);
        }
        .hat {
            font-size: 4rem;
            text-align: center;
            margin-bottom: 0.5rem;
            opacity: 0.9;
            filter: drop-shadow(0 4px 8px rgba(0,0,0,0.3));
        }
        h1 {
            font-size: 2.4rem;
            font-weight: 500;
            letter-spacing: -0.01em;
            text-align: center;
            background: linear-gradient(120deg, #f5e7d9, #e2cbb5);
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
            margin-bottom: 0.75rem;
        }
        .sub {
            text-align: center;
            color: #bfa98e;
            font-size: 0.9rem;
            margin-bottom: 1.8rem;
            border-bottom: 1px dashed #4f3e33;
            display: inline-block;
            width: auto;
            margin-left: auto;
            margin-right: auto;
            padding-bottom: 0.5rem;
        }
        .legal-wrapper {
            max-height: 420px;
            overflow-y: auto;
            padding-right: 0.8rem;
            margin-bottom: 1.5rem;
            background: rgba(0, 0, 0, 0.2);
            border-radius: 1.2rem;
            padding: 1rem 1rem 1rem 1.2rem;
            border: 1px solid rgba(210, 180, 140, 0.2);
        }
        .legal-text {
            font-size: 0.85rem;
            line-height: 1.5;
            color: #e2d4c6;
        }
        .legal-text strong {
            color: #e7cba5;
            font-weight: 600;
        }
        .legal-text h3 {
            color: #f0ddc4;
            font-size: 1rem;
            margin: 1rem 0 0.3rem 0;
            font-weight: 500;
        }
        .legal-text p {
            margin-bottom: 0.75rem;
        }
        .intro-message {
            background: rgba(0, 0, 0, 0.3);
            border-radius: 1rem;
            padding: 0.8rem 1rem;
            margin-bottom: 1.5rem;
            border-left: 3px solid #c7a56b;
        }
        .fr, .en {
            font-size: 0.9rem;
        }
        .fr {
            color: #ecd9c6;
            margin-bottom: 0.5rem;
        }
        .en {
            color: #d1bfae;
            font-style: normal;
            font-size: 0.85rem;
        }
        .btn-wrapper {
            text-align: center;
            margin: 1rem 0 0.5rem;
        }
        .btn-accept {
            display: inline-block;
            padding: 0.9rem 2rem;
            background: #2f2a27;
            color: #fef3e4;
            text-decoration: none;
            font-weight: 600;
            border-radius: 60px;
            font-size: 1.2rem;
            border: 1px solid #b48c54;
            transition: all 0.25s;
            box-shadow: 0 2px 6px rgba(0,0,0,0.3);
            letter-spacing: 0.5px;
            cursor: pointer;
        }
        .btn-accept:hover {
            background: #3e3530;
            border-color: #dcb179;
            color: #fff6ea;
            transform: scale(1.02);
            box-shadow: 0 8px 20px rgba(0,0,0,0.4);
        }
        .footer {
            text-align: center;
            font-size: 0.7rem;
            color: #9b8a78;
            margin-top: 1.5rem;
            border-top: 1px dashed #4f3e33;
            padding-top: 1rem;
            font-weight: 300;
        }
        hr {
            border: none;
            height: 1px;
            background: #4a3a2e;
            margin: 0.6rem 0;
        }
        .warning-refuse {
            font-size: 0.8rem;
            color: #d99e6b;
            text-align: center;
            margin-top: 0.8rem;
        }
        @media (max-width: 650px) {
            .card { padding: 1.5rem; }
            h1 { font-size: 1.9rem; }
            .legal-wrapper { max-height: 350px; }
        }
    </style>
</head>
<body>
<div class="card" id="acceptance-card">
    <div class="hat">🎩</div>
    <h1>Monsieur Mi</h1>
    <div style="text-align: center;">
        <div class="sub">— esprit local, accès protégé —</div>
    </div>

    <div class="intro-message">
        <div class="fr">
            ✦ Monsieur Mi est un automate local, non censuré, expérimental.<br>
            Avant de lui parler, vous devez accepter les conditions légales ci-dessous.
        </div>
        <div class="en">
            ✦ Monsieur Mi is a local, uncensored, experimental AI.<br>
            Before speaking with him, you must accept the legal terms below.
        </div>
    </div>

    <!-- Zone juridique complète (valeur légale Québec/Canada) -->
    <div class="legal-wrapper">
        <div class="legal-text">
            <strong>CONDITIONS D'UTILISATION ET EXCLUSION DE RESPONSABILITÉ</strong><br><br>

            <strong>1. Acceptation des conditions</strong><br>
            En cliquant sur « J'accepte et j'accède au site », vous reconnaissez avoir lu, compris et accepté l'intégralité des présentes conditions. Si vous n'acceptez pas ces règles, vous devez quitter ce site immédiatement.<br><br>

            <strong>2. Nature du service et absence de garantie</strong><br>
            Ce service de clavardage automatisé (chatbot) est basé sur un modèle d'intelligence artificielle expérimental et non censuré.<br>
            — <strong>Divertissement uniquement</strong> : Ce robot est fourni exclusivement à des fins de divertissement et de recherche technologique.<br>
            — <strong>Erreurs et hallucinations</strong> : L'intelligence artificielle peut générer des réponses fausses, inexactes, trompeuses, offensantes, inappropriées ou diffamatoires. L'exploitant du site ne valide pas le contenu généré par la machine.<br>
            — <strong>Aucun conseil professionnel</strong> : Les réponses ne constituent en aucun cas des conseils médicaux, juridiques, financiers, psychologiques ou professionnels. Ne prenez aucune décision basée sur les propos du robot.<br><br>

            <strong>3. Limitation stricte de responsabilité</strong><br>
            En vertu des lois applicables (notamment la province de Québec et le Canada), l'exploitant de ce site ne pourra en aucun cas être tenu responsable de tout dommage direct, indirect, accessoire ou moral (incluant, mais sans s'y limiter, la perte de données, les pertes financières ou les atteintes à la réputation) découlant de l'utilisation de ce chatbot ou de la confiance accordée à ses réponses. Vous utilisez ce service entièrement à vos propres risques.<br><br>

            <strong>4. Obligations de l'utilisateur</strong><br>
            En utilisant ce service, vous vous engagez à :<br>
            — Ne pas tenter de forcer le robot à générer du contenu illégal (haine, violence, pédocriminalité, fabrication d'armes, cyberattaques).<br>
            — Ne pas diffuser, publier ou partager publiquement les réponses générées par le robot si celles-ci portent atteinte aux droits d'autrui ou violent la loi.<br><br>

            <strong>5. Protection de la vie privée et confidentialité</strong><br>
            — <strong>Ne partagez aucune donnée personnelle</strong> : Vous ne devez saisir aucune information confidentielle, nominative ou sensible (nom, adresse, numéro d'assurance sociale, données bancaires, secrets commerciaux) dans le clavardage.<br>
            — <strong>Enregistrement des conversations</strong> : Les conversations peuvent être enregistrées pour des raisons techniques ou de maintenance du serveur. L'exploitant ne peut garantir la confidentialité absolue des données saisies.<br><br>

            <strong>6. Droit applicable</strong><br>
            Les présentes conditions sont régies et interprétées conformément aux lois de la province de Québec et aux lois du Canada qui s'y appliquent. Tout litige relatif à l'utilisation de ce site sera soumis à la compétence exclusive des tribunaux du district judiciaire de Terrebonne (ou de votre région).
        </div>
    </div>

    <div class="btn-wrapper">
        <button id="acceptBtn" class="btn-accept">📜 J'accepte et j'accède au site</button>
    </div>
    <div class="warning-refuse">
        ⚠️ En refusant, vous ne pourrez pas accéder au chatbot.
    </div>
    <div class="footer">
        Hébergé localement — Mirabel, Québec — Valeur légale complète
    </div>
</div>

<script>
    // Vérifier si l'utilisateur a déjà accepté pendant cette session (onglet ouvert)
    const hasAccepted = sessionStorage.getItem('monsieur_mi_consent');
    const targetChatPage = "IntelligencAllyServerLocal.html";  // votre page chatbot existante

    if (hasAccepted === 'true') {
        // Redirection immédiate vers le chatbot
        window.location.href = targetChatPage;
    }

    // Gestion du clic sur le bouton d'acceptation
    const acceptBtn = document.getElementById('acceptBtn');
    if (acceptBtn) {
        acceptBtn.addEventListener('click', function() {
            // Sauvegarde du consentement pour la session courante
            sessionStorage.setItem('monsieur_mi_consent', 'true');
            // Redirection vers le chatbot
            window.location.href = targetChatPage;
        });
    }
</script>
</body>
</html>

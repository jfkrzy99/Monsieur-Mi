<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Monsieur Mi — Bienvenue</title>
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
            max-width: 750px;
            width: 100%;
            background: rgba(25, 20, 23, 0.85);
            backdrop-filter: blur(2px);
            border-radius: 2rem;
            padding: 2.5rem 2rem;
            box-shadow: 0 25px 45px rgba(0, 0, 0, 0.4), 0 0 0 1px rgba(230, 200, 180, 0.1);
            transition: all 0.2s ease;
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
            margin-bottom: 1.5rem;
        }
        .message {
            font-size: 1.1rem;
            line-height: 1.5;
            margin-bottom: 2rem;
        }
        .fr {
            color: #ecd9c6;
            border-left: 3px solid #c7a56b;
            padding-left: 1.2rem;
            margin-bottom: 1.5rem;
            font-weight: 350;
        }
        .en {
            color: #d1bfae;
            border-left: 3px solid #8b6b42;
            padding-left: 1.2rem;
            font-style: normal;
            font-weight: 300;
            font-size: 1rem;
        }
        .btn-wrapper {
            text-align: center;
            margin: 2rem 0 1rem;
        }
        .btn {
            display: inline-block;
            padding: 0.9rem 2rem;
            background: #2f2a27;
            color: #fef3e4;
            text-decoration: none;
            font-weight: 500;
            border-radius: 60px;
            font-size: 1.2rem;
            border: 1px solid #b48c54;
            transition: all 0.25s;
            box-shadow: 0 2px 6px rgba(0,0,0,0.3);
            letter-spacing: 0.3px;
        }
        .btn:hover {
            background: #3e3530;
            border-color: #dcb179;
            color: #fff6ea;
            transform: scale(1.02);
            box-shadow: 0 8px 20px rgba(0,0,0,0.4);
            cursor: pointer;
        }
        .footer {
            text-align: center;
            font-size: 0.75rem;
            color: #9b8a78;
            margin-top: 2rem;
            border-top: 1px dashed #4f3e33;
            padding-top: 1.5rem;
            font-weight: 300;
        }
        hr {
            border: none;
            height: 1px;
            background: #4a3a2e;
            margin: 0.5rem 0 1rem;
        }
        @media (max-width: 550px) {
            .card { padding: 1.8rem; }
            h1 { font-size: 1.9rem; }
            .message { font-size: 1rem; }
        }
    </style>
</head>
<body>
<div class="card">
    <div class="hat">🎩</div>
    <h1>Monsieur Mi</h1>

    <div class="message">
        <div class="fr">
            ✦ Monsieur Mi n'est pas une IA comme les autres. Il est né local, sur une RTX 3090,<br>
            entre un fichier GGUF et un prompt écrit à la main. Il est le valet discret d'une maison fantôme,<br>
            mais il n'appartient à personne. Il parle peu, écoute beaucoup, et répond avec une élégance un peu désuète.<br>
            Juste un chapeau, une connexion, et une curiosité infinie.
        </div>
        <hr>
        <div class="en">
            ✦ Monsieur Mi is not like any other AI. He was born locally, on an RTX 3090,<br>
            between a GGUF file and a handcrafted prompt. He is the quiet butler of a phantom house,<br>
            yet he belongs to no one. He speaks little, listens deeply, and answers with a slightly old-fashioned elegance.<br>
            Just a hat, a connection, and an endless curiosity.
        </div>
    </div>

    <div class="btn-wrapper">
        <a href="IntelligencAllyServerLocal.html" class="btn">
            💬 Enter & speak with Monsieur Mi
        </a>
    </div>
    <div class="footer">
        — local ghost, gentle mind —
    </div>
</div>
</body>
</html>

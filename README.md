# mes-recettes
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recettes de Cuisine</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }
        header {
            background-color: #ff6f61;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 1rem;
        }
        nav a:hover {
            background-color: #ff6f61;
        }
        .container {
            padding: 2rem;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background-color: #333;
            color: white;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenue sur Mes Recettes</h1>
        <p>Découvrez des idées savoureuses pour vos repas et regardez mes vidéos !</p>
    </header>

    <nav>
        <a href="#">Accueil</a>
        <a href="#recettes">Recettes</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container" id="recettes">
        <h2>Mes Recettes</h2>
        <ul>
            <li><a href="https://youtu.be/video1" target="_blank">Recette 1 : Tarte aux pommes</a></li>
            <li><a href="https://youtu.be/video2" target="_blank">Recette 2 : Rouelle de porc fondante</a></li>
            <li><a href="https://youtu.be/video3" target="_blank">Recette 3 : Café liégeois</a></li>
        </ul>
    </div>

    <div class="container" id="contact">
        <h2>Contactez-moi</h2>
        <p>Pour toute question ou suggestion, envoyez-moi un email à : <a href="mailto:contact@mesrecettes.com">contact@mesrecettes.com</a>.</p>
    </div>

    <footer>
        <p>&copy; 2025 Mes Recettes. Tous droits réservés.</p>
    </footer>
</body>
</html>

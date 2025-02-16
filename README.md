<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cuisine Saine</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fce4ec;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #f06292;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        h1 {
            margin: 0;
        }
        nav {
            background-color: #ec407a;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        .section {
            padding: 30px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
        }
        footer {
            background-color: #f06292;
            color: white;
            text-align: center;
            padding: 15px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Cuisine Saine</h1>
        <p>Découvrez des recettes saines et délicieuses !</p>
    </header>

    <nav>
        <a href="#recettes">Recettes</a>
        <a href="#blog">Blog</a>
        <a href="#contact">Contact</a>
    </nav>

    <div id="recettes" class="section">
        <h2>Nos Recettes</h2>
        <p>Découvrez une sélection de recettes saines pour tous les goûts !</p>
        <ul>
            <li>Salade de quinoa</li>
            <li>Poisson grillé aux herbes</li>
            <li>Soupe detox</li>
        </ul>
    </div>

    <div id="blog" class="section">
        <h2>Le Blog</h2>
        <p>Lisez nos derniers articles sur la cuisine saine, les tendances alimentaires et bien plus !</p>
    </div>

    <div id="contact" class="section">
        <h2>Contactez-nous</h2>
        <p>Vous avez une question ? N'hésitez pas à nous contacter !</p>
        <form>
            <label for="name">Votre nom :</label><br>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">Votre email :</label><br>
            <input type="email" id="email" name="email" required><br><br>
            <input type="submit" value="Envoyer">
        </form>
    </div>

    <footer>
        <p>&copy; 2025 Cuisine Saine - Tous droits réservés</p>
    </footer>

</body>
</html>

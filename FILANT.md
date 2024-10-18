<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Connexion - FILANT225</title>
    <style>
        /* Styles généraux */
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            font-family: Arial, sans-serif;
            background-color: #FFA500; /* Arrière-plan orange */
        }

        .container {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100%;
            text-align: center;
        }

        .logo {
            width: 150px; /* Ajustez selon la taille de votre logo */
            height: 150px;
            background-color: white; /* Placez ici votre logo */
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .logo img {
            width: 80%;
            height: auto;
        }

        .company-name {
            margin-top: 20px;
            font-size: 24px;
            color: white;
        }

        .login-form {
            margin-top: 40px;
        }

        input[type="text"], input[type="password"] {
            width: 200px;
            padding: 10px;
            margin: 10px;
            border-radius: 5px;
            border: none;
            outline: none;
        }

        .btn-login {
            background-color: #333;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .btn-login:hover {
            background-color: #555;
        }

        .signup-link {
            margin-top: 20px;
            color: white;
            font-size: 14px;
        }

        .signup-link a {
            color: white;
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Espace du logo au centre -->
        <div class="logo">
            <!-- Ajoutez votre logo ici -->
            <img src="logo.png" alt="Logo FILANT225">
        </div>

        <!-- Nom de l'entreprise en bas du logo -->
        <div class="company-name">FILANT225</div>

        <!-- Formulaire de connexion -->
        <div class="login-form">
            <input type="text" placeholder="Nom d'utilisateur" required>
            <input type="password" placeholder="Mot de passe" required>
            <button class="btn-login" onclick="login()">Se connecter</button>
        </div>

        <!-- Lien d'inscription en bas de la page -->
        <div class="signup-link">
            Pas encore inscrit ? <a href="#">Créer un compte</a>
        </div>
    </div>

    <script>
        function login() {
            // Simulation de la connexion
            alert("Connexion réussie !");
            // Rediriger vers la page d'accueil après connexion
            window.location.href = "page-daccueil.html"; // Remplacez par la bonne page de redirection
        }
    </script>

</body>
</html>

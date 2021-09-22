<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>validation formulaire</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"/>
</head>
<body>
    <div class="container">
        <h1 class="label">Connexion</h1>
        <form class="login_form" method="post" name="form" onsubmit="return validated()">
            <div class="font">Email/Identifiant</div>
            <input type="text"name="email">
            <div id="email_error">Veuillez remplir votre email/identifiant</div>
            <div class="font font2">Mot de Passe</div>
            <input type="password"name="password">
            <div id="pass_error">Veuillez remplir votre mot de passe</div>
            <button type="submit">Se connecter</button>

        </form>
    </div>
    <script src="vallid.js"></script>
    
</body>
</html>
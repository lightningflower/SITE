<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lightning.Flower - Chaîne YouTube</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="logo.png" alt="Logo Lightning.Flower">
        </div>
        <nav>
            <ul>
                <li><a href="#home">Accueil</a></li>
                <li><a href="#about">À propos</a></li>
                <li><a href="#videos">Vidéos</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <div class="hero">
            <h1>Bienvenue sur Lightning.Flower</h1>
            <p>Abonnez-vous pour des vidéos de qualité sur YouTube !</p>
            <a href="https://www.youtube.com/@Lightning.Flower" class="cta-button">S'abonner</a>
        </div>
    </section>

    <section id="about">
        <h2>À propos de moi</h2>
        <p>Je suis un créateur de contenu passionné par...</p>
    </section>

    <section id="videos">
        <h2>Mes vidéos récentes</h2>
        <div class="video-grid">
            <div class="video">
                <iframe src="https://www.youtube.com/embed/videoID" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>
            <!-- Répétez le bloc pour chaque vidéo -->
        </div>
    </section>

    <section id="contact">
        <h2>Contactez-moi</h2>
        <form>
            <label for="email">Votre email :</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Votre message :</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Envoyer</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Lightning.Flower. Tous droits réservés.</p>
    </footer>
</body>
</html>

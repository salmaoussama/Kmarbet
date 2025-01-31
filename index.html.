<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kmarbet - Paris Sportifs</title>
    <style>
        /* Reset CSS */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 10px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: #ffcc00;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h2 {
            margin-bottom: 20px;
            color: #333;
        }

        .sports-list {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        .sport-card {
            background-color: #f9f9f9;
            border: 1px solid #ddd;
            padding: 15px;
            width: calc(33.333% - 20px);
            text-align: center;
            cursor: pointer;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .sport-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }

        /* Modal CSS */
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.5);
            justify-content: center;
            align-items: center;
        }

        .modal-content {
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            width: 300px;
            text-align: center;
        }

        .close-btn {
            cursor: pointer;
            color: #333;
            font-size: 20px;
            float: right;
        }
    </style>
</head>
<body>

    <!-- En-tête -->
    <header>
        <h1>Kmarbet - Paris Sportifs</h1>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#accueil">Accueil</a>
        <a href="#sports">Sports</a>
        <a href="#promotions">Promotions</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Contenu principal -->
    <div class="container">
        <!-- Section Accueil -->
        <section id="accueil">
            <h2>Bienvenue sur Kmarbet</h2>
            <p>Kmarbet est votre destination ultime pour les paris sportifs en ligne. Pariez sur vos sports préférés et profitez des meilleures cotes du marché.</p>
        </section>

        <!-- Section Sports -->
        <section id="sports">
            <h2>Sports Disponibles</h2>
            <div class="sports-list">
                <div class="sport-card" onclick="openModal('Football')">Football</div>
                <div class="sport-card" onclick="openModal('Basketball')">Basketball</div>
                <div class="sport-card" onclick="openModal('Tennis')">Tennis</div>
                <div class="sport-card" onclick="openModal('Rugby')">Rugby</div>
                <div class="sport-card" onclick="openModal('Cyclisme')">Cyclisme</div>
                <div class="sport-card" onclick="openModal('eSports')">eSports</div>
            </div>
        </section>

        <!-- Section Promotions -->
        <section id="promotions">
            <h2>Promotions</h2>
            <p>Découvrez nos promotions exclusives et boostez vos gains dès aujourd'hui!</p>
        </section>

        <!-- Section Contact -->
        <section id="contact">
            <h2>Contactez-nous</h2>
            <p>Pour toute question ou assistance, n'hésitez pas à nous contacter à l'adresse suivante : <a href="mailto:contact@kmarbet.com">contact@kmarbet.com</a></p>
        </section>
    </div>

    <!-- Pied de page -->
    <footer>
        <p>&copy; 2023 Kmarbet. Tous droits réservés.</p>
    </footer>

    <!-- Modal -->
    <div id="modal" class="modal">
        <div class="modal-content">
            <span class="close-btn" onclick="closeModal()">&times;</span>
            <h2 id="modal-title"></h2>
            <p>Pariez maintenant sur <strong id="modal-sport"></strong> et tentez de gagner gros !</p>
        </div>
    </div>

    <!-- JavaScript -->
    <script>
        // Fonction pour ouvrir le modal
        function openModal(sport) {
            const modal = document.getElementById('modal');
            const modalTitle = document.getElementById('modal-title');
            const modalSport = document.getElementById('modal-sport');

            modalTitle.textContent = sport;
            modalSport.textContent = sport;
            modal.style.display = 'flex';
        }

        // Fonction pour fermer le modal
        function closeModal() {
            const modal = document.getElementById('modal');
            modal.style.display = 'none';
        }

        // Fermer le modal en cliquant en dehors
        window.onclick = function(event) {
            const modal = document.getElementById('modal');
            if (event.target === modal) {
                modal.style.display = 'none';
            }
        };
    </script>

</body>
</html>

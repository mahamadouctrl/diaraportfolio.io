<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio /Diarassouba Mahamadou</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Accueil</a></li>
                <li><a href="#about">À propos</a></li>
                <li><a href="#skills">Compétences</a></li>
                <li><a href="#projects">Projets</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
<body>
   <p id="date"></p>

    <script>
        function afficherDate() {
            const dateActuelle = new Date();
            const options = {
                weekday: 'long', year: 'numeric', month: 'long', day: 'numeric',
                hour: '2-digit', minute: '2-digit', second: '2-digit'
            };
            document.getElementById('date').innerHTML = dateActuelle.toLocaleDateString('fr-FR', options);
        }

        // Appelle la fonction afficherDate toutes les secondes (1000 millisecondes)
        setInterval(afficherDate, 1000);
    </script>
</body>
    <section id="home">
        <h1>Bienvenue sur mon portfolio</h1>
        <div style="text-align: center;">
            <img src="photo-profil.jpg" alt="description de l'image" style="width:150px; height:150;border-radius: 50%;">
            <h1>Mahamadou Diarassouba (Ingénieur technopédagogue)</h1>
        </div>
        
        <p>Découvrez à travers ce site mon travail et mes offres de compétences.</p>
    </section>

    <section id="about">
        <h2>À propos</h2>
        <p><strong>Mahamadou DIARASSOUBA</strong>, est un éminent Professeur de communication audiovisuelle. Il est par ailleurs Formateur/encadrant des enseignant.e.s du primaire en Côte d'Ivoire.Il est également Consultant/Tuteur auprès de l'Institut de la Francophonie pour l'Education et la Formation, organe subsidiaire de l'Organisation internationale de la francophonie.
            Cet ingénieur technopédagogue, est titulaire d'un Master en Analyse, Conception et Recherche dans le Domaine de l'Ingénierie des Technologies Educatives de la prestigieuse université de Cy cergy Paris Université.</p>
        <p>Je suis un ingénieur en technologie éducative passionné par la conception pédagogique et les systèmes d'apprentissage à distance.</p>
    </section>

    <section id="skills">
        <h2>Compétences</h2>

    <div class="competence-section competence1">
        <div class="competence-title">Digital Marketing</div>
        <p class="competence-description">Utilisation des outils de marketing numérique pour promouvoir des produits et services, en mettant l'accent sur les campagnes publicitaires en ligne, la gestion des réseaux sociaux et l'optimisation SEO.</p>
    </div>

    <div class="competence-section competence2">
        <div class="competence-title">Montage photo et vidéo</div>
        <p class="competence-description">Maîtrise des logiciels de montage photo et vidéo pour créer des contenus visuels attrayants et engageants destinés à des formations en ligne ou à des campagnes de communication.</p>
    </div>

    <div class="competence-section competence3">
        <div class="competence-title">Conception Pédagogique et Ingénierie</div>
        <p class="competence-description">Création de parcours de formation sur mesure, en intégrant les méthodes pédagogiques modernes et les nouvelles technologies, afin de favoriser l'apprentissage à distance et en présentiel.</p>
    </div>

    <div class="competence-section competence4">
        <div class="competence-title">Conception de systèmes d'apprentissage à distance</div>
        <p class="competence-description">Développement de plateformes d'apprentissage en ligne, incluant des outils d'évaluation et de suivi des apprenants, pour faciliter l'accès à l'éducation à distance.</p>
    </div>

    <div class="competence-section competence5">
        <div class="competence-title">Introduction des TIC dans l'Éducation</div>
        <p class="competence-description">Encadrement et formation des enseignants pour l'intégration des technologies de l'information et de la communication (TIC) dans leurs pratiques pédagogiques, afin d'améliorer l'efficacité de l'enseignement.</p>
    </div>

    <div class="competence-section competence6">
        <div class="competence-title">Tutorat et accompagnement à distance</div>
        <p class="competence-description">Fourniture d'un soutien pédagogique et technique aux apprenants à distance, en utilisant des outils de communication numérique pour assurer un suivi personnalisé.</p>
    </div>

    <div class="competence-section competence7">
        <div class="competence-title">Maintenance informatique</div>
        <p class="competence-description">Connaissances techniques en maintenance informatique pour assurer le bon fonctionnement des systèmes et équipements informatiques dans les environnements éducatifs et professionnels.</p>
    </div>
    </section>

    <section id="projects">
        <h2>Projets</h2>
        <ul>
            <li class="projet1">Projet 1 : Conception d'une plateforme d'apprentissage en ligne dénommée e-cafop</li>
            <li class="projet2">Projet 2 : Intégration des TIC dans la formation au CAFOP</li>
            <li class="projet3">Projet 3 : Élaboration d'un module de formation à distance sur l'initiation à l'informatique</li>
            <li class="projet4">Projet 4 : Mise en place d'une plateforme de formation en développement web</li>
        </ul>
    </section>
    <section id="exprériencesprofessionnels">
        <h2>Expériences professionnelles</h2>
        <li>Responsable informatique du Cafop de Korhogo
            (Depuis janvier 2024 Cafop de Korhogo Korhogo)</li>
        <li>Formateur-encadrant des enseignants du primaire
            (Depuis juillet 2022 Ministère de l'Education Nationale et de l'Alphabétisation)</li>
        <li>Tuteur/formateur en genre (égalité femme-homme dans l'éducation)
            Depuis juillet 2022
            Institut de la Francophonie pour l'Education et la Formation (IFEF) DAKAR
            Accompagnement des cohortes de participant.e.s à la formation sur l'égalité
            Femmes-Hommes dans l'éducation
            Accompagnement des cohortes de participant.e.s à la conception de fiches
            pédagogiques pour le portail RELIEFH</li>
        
    </section>
    <section id="contact">
        <h1>Formulaire de demande d'informations</h1>
        <h2>Contactez-moi vers le formulaire ci-dessous</h2>

    <form id="infoForm">
        <div class="form-control">
            <label for="name">Nom :</label>
            <input type="text" id="name" name="name" placeholder="Votre nom">
            <div class="error" id="nameError">Le nom est requis.</div>
        </div>

        <div class="form-control">
            <label for="email">Email :</label>
            <input type="email" id="email" name="email" placeholder="Votre email">
            <div class="error" id="emailError">Veuillez entrer un email valide.</div>
        </div>

        <div class="form-control">
            <label for="message">Message :</label>
            <textarea id="message" name="message" placeholder="Votre message"></textarea>
            <div class="error" id="messageError">Le message est requis.</div>
        </div>

        <div class="form-control">
            <input type="submit" value="Envoyer la demande">
        </div>
    </form>

    <script>
        document.getElementById('infoForm').addEventListener('submit', function(event) {
            event.preventDefault(); // Empêche l'envoi du formulaire

            // Récupérer les valeurs des champs
            let name = document.getElementById('name').value;
            let email = document.getElementById('email').value;
            let message = document.getElementById('message').value;

            // Réinitialiser les messages d'erreur
            document.getElementById('nameError').style.display = 'none';
            document.getElementById('emailError').style.display = 'none';
            document.getElementById('messageError').style.display = 'none';

            // Valider les champs
            let isValid = true;

            if (name.trim() === '') {
                document.getElementById('nameError').style.display = 'block';
                isValid = false;
            }
            if (email.trim() === '' || !validateEmail(email)) {
                document.getElementById('emailError').style.display = 'block';
                isValid = false;
            }
            if (message.trim() === '') {
                document.getElementById('messageError').style.display = 'block';
                isValid = false;
            }

            // Si tous les champs sont valides, soumettre le formulaire
            if (isValid) {
                alert('Formulaire envoyé avec succès !');
                // Ici, vous pouvez ajouter du code pour traiter les données (envoi à un serveur par exemple)
            }
        });

        // Fonction pour valider l'adresse email
        function validateEmail(email) {
            const re = /^[a-zA-Z0-9._-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$/;
            return re.test(String(email).toLowerCase());
        }
    </script>
        
        

        <script src="script.js"></script>
</html>

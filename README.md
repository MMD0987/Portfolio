<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>LOGDIA</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header, nav, section, article, aside, footer {
            padding: 20px;
            margin: 10px;
        }
        header {
            background-color: #f8f9fa;
            text-align: center;
        }
        nav {
            background-color: #e9ecef;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin-right: 15px;
        }
        nav ul li a {
            text-decoration: none;
            color: #007bff;
        }
        section {
            display: flex;
        }
        article {
            flex: 70%;
        }
        aside {
            flex: 30%;
            background-color: #f8f9fa;
        }
        footer {
            background-color: #e9ecef;
            text-align: center;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
        }
        th {
            background-color: #f2f2f2;
            text-align: left;
        }
    </style>
</head>
<body>
    <header>
        <h1>Diallo Mamadou Mouctar</h1>
        <p>Web Developper/Logisticien</p>
        <div class="Images">
                <img src="Images/Ajouter un titre.png" alt="">
    </header>
<!-- Barre de navigation -->
    <center>
    <nav>
        <a href="#accueil">Accueil</a>
        <a href="#àpropos">À propos</a>
        <a href="#competences">Compétences</a>
        <a href="#cv">CV</a>
        <a href="#contact">Contact</a>
    </nav>
   </center>
    
<!-- À propos -->
    <section>
        <article>
            <h2 id="àpropos">À propos</h2>
            <img src="Images/IMG_4428.jpg" alt="Photo de moi" width="150" height="150" style="float: left; margin-right: 20px;">
            <p>Jeune logisticien dans la gestion de la chaine d'approvisionnement et la coordination de l'expédition et jeune développeur web avec une passion pour la création de sites web dynamiques et interactifs. Soucieux de la qualité et de l'efficacité, je suis à la recherche de nouveaux défis professionnels.</p><br><br>
<!-- Compétences -->
            <h2 id="competences">Compétences</h2>
            <ul>
                <li>HTML & CSS</li>
                <li>JavaScript</li>
                <li>MS Project</li>
            </ul>

            <h3>Compétences techniques</h3>
            <ol>
                <li>Développement front-end</li>
                <li>Gestion de bases de données</li>
                <li>Gestion de la chaîne d'approvisionnement</li>
                <li>Logistique de transport</li>
            </ol>

            <h2>Tableau de compétences</h2>
            <table>
                <tr>
                    <th>Compétence</th>
                    <th>Niveau</th>
                </tr>
                <tr>
                    <td>HTML & CSS</td>
                    <td>Débutant</td>
                </tr>
                <tr>
                    <td>JavaScript</td>
                    <td>Débutant</td>
                </tr>
                <tr>
                    <td>MS Project</td>
                    <td>Intermédiaire</td>
                </tr>
            </table>
            <h2>CV</h2>
<!-- Mon CV -->
            <p>Téléchargez mon CV <a href="file:///C:/Users/HP/Documents/CV-1.html" download>ICI</a>.</p>
<!-- Contact -->
            <h2>Formulaire de contact</h2>
            <form>
                <label for="name">Nom :</label><br>
                <input type="text" id="name" name="name"><br><br>

                <label for="email">Email :</label><br>
                <input type="email" id="email" name="email"><br><br>

                <label for="password">Mot de passe :</label><br>
                <input type="password" id="password" name="password"><br><br>

                <label for="message">Message :</label><br>
                <textarea id="message" name="message" rows="4" cols="50"></textarea><br><br>

                <label for="newsletter">S'abonner à la newsletter :</label>
                <input type="checkbox" id="newsletter" name="newsletter"><br><br>

                <label>Genre :</label><br>
                <input type="radio" id="male" name="gender" value="male">
                <label for="male">Homme</label><br>
                <input type="radio" id="female" name="gender" value="female">
                <label for="female">Femme</label><br><br>

                <input type="submit" value="Envoyer">
            </form>

            <h2>Vidéo</h2>
            <video width="320" height="240" controls>
                <source src="Vidéos/Ajouter un titre.mp4" type="video/mp4">
                Votre navigateur ne supporte pas la balise vidéo.
            </video>
        </article>
        <aside>
            <h2>Liens vers réseaux sociaux</h2>
            <ul>
                <li><a href="https://www.facebook.com/mamadoumouctar.diallo.182/" target="_blank">facebook</a></li>
                <li><a href="www.linkedin.com/in/mouctar-diallo-132ba930a" target="_blank">linkedin</a></li>
            </ul>
        </aside>
    </section>
    <footer>
        <p>© 2024 Diallo Mamadou Mouctar. Tous droits réservés.</p>
    </footer>
</body>
</html>

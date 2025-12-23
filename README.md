# site-d-accompagnement
devellopement accompagnement
<!doctype html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>Marie Dupuis- Caoch en Développement Personnel</title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <link rel="stylesheet" href="styles.css" />
    </head>
    <body>
        <main>
            <!--En tête de la page-->
            <header>
                <h1>Coach Marie Dupuis</h1>
                <p>Coach certifié en développement personnel</p>
                <nav class="container">
                    <ul>
                        <li><a href="accueil">Accueil</a></li>
                        <li><a href="service">Service</a></li>
                        <li><a href="à propos">A propos</a></li>
                        <li><a href="contact">Contact</a></li>
                    </ul>
                </nav>
            </header>
            <!--Corp de la page-->
            <main>
                <section id="accueil">
                    <h2>Bienvenue sur mon site de coaching</h2>
                    <p>
                        Je suis Marie Dupuis, coach certifié en développement personnel. J'accompagne les femmes et les
                        hommes qui souhaitent retrouver confiance en eux, surmonter les blocages et avance avec clarté
                        vers une vie plus épanouie. A travers un accompagnement bienveillant et personnalisé, je vous
                        aide à révéler votre plein potentiel.
                    </p>
                    <h3 class="slogan">SLOGAN: Révélez le meilleur de vous-même</h3>
                </section>
                <!--Div service-->
                <div class="service">
                    <h4>Mes service</h4>
                    <ol>
                        <li>Coaching individuel</li>
                        <li>Ateliers de groupe</li>
                        <li>Accompagnement carrière</li>
                    </ol>
                </div>
                <!--section a propos-->
                <section id="a-propos">
                    <img src="https://via.placeholder.com/300*200" alt="Image de remplacement" />
                    <p>
                        <strong>
                            Je suis Marie Dupuis, coach en dévéloppement personneldepuis de 7 ans. J'accompagne les
                            personnes à retrouver confiance en elles, à atteindre leurs objectifs de vie à mieux se
                            connaître. Mon approche est humaine, bienveillant et orientée vers l'action
                        </strong>
                    </p>
                </section>
                <!--section contact-->
                <section id="contact">
                    <form method="post">
                        <fieldset>
                            <legend>Présentation</legend>
                            <label for="Name">Nom (required):</label>
                            <input type="text" name="nom" id="Name" required placeholder="Entrer votre nom" />
                            <label for="last-name">Prenom (required):</label>
                            <input type="text" name="prenom" id="prenom" required placeholder="Entrer votre prenom" />
                            <label for="email">Email (required):</label>
                            <input type="email" name="email" id="email" required placeholder="Entrer votre email" />
                            <label for="comment">Commentaire</label>
                            <textarea id="message" name="message" required placeholder="Message"></textarea>
                            <button type="submit">Envoyé</button>
                        </fieldset>
                    </form>
                    <p>
                        Voici mon lien whatsapp pour plus d'info et contact :
                        <a href="#">https://wa.me/33612345678</a>
                        Contact:
                        <a href="#">+33 6 12 34 56 78</a>
                    </p>
                </section>
            </main>
            <!--pied de page-->
            <footer>
                <p>©2025 Marie Dupuis-Coach en dévéloppement personnel</p>
                <p>Email: <a href="#">contact@mariedupuis.com</a></p>
                <h5>Suivez-moi:</h5>
                <p>-Instagram</p>
                <p>-Linkedln</p>
                <p>-Facebook</p>
                <p><strong>Mention légales | Politique de confidentialité</strong></p>
            </footer>
        </main>
    </body>
</html>

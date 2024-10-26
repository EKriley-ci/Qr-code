QR Code Component
Ceci est une solution au défi QR Code Component sur Frontend Mentor. Les défis Frontend Mentor vous aident à améliorer vos compétences en codage en réalisant des projets réalistes.

Aperçu
Le défi
Le défi consistait à créer une carte de prévisualisation de code QR, avec un design propre et centré.

Capture d'écran

Liens
URL de la solution

URL du site en ligne

Mon Processus
Construit avec
HTML5 sémantique

Propriétés personnalisées CSS

Flexbox

Ce que j'ai appris
Travailler sur ce projet m'a permis de :

Utiliser Flexbox pour créer une mise en page réactive et centrée.

Styliser des composants avec des propriétés CSS personnalisées.

Voici un extrait de code dont je suis fier :

html

Copier
<main>
  <div class="img">
    <img src="images/image-qr-code.png" alt="image du qr code">
  </div>
  <div class="text">
    <h2>Improve your front-end skills by building projects</h2>
    <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
  </div>
</main>
css

Copier
body {
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: hsl(212, 45%, 89%);
}
main {
    max-width: 350px;
    width: 90%;
    overflow: hidden;
    padding: 1em;
    background: #fff;
    border-radius: 20px;
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: space-between;
    box-shadow: 0 2px 3px rgba(0, 0, 0, 0.589);
}
Auteur
GitHub - @EKriley-ci

Frontend Mentor - @EKriley-ci
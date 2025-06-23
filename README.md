🌿 Événements & Co – Site Vitrine 🌿

Bienvenue dans le dépôt du site vitrine Événements & Co, une entreprise fictive spécialisée dans l'organisation d'événements.
Ce projet met l'accent sur l’éco-conception web, l’accessibilité et l’utilisation de Bootstrap 5 pour une expérience utilisateur fluide et moderne.

Link : evenement-and-co-projet2.netlify.app

📁 Structure du projet
bash
Copier
Modifier
├── index.html
├── programmes.html
├── contacts.html
├── stylenano.css
├── IMAGES/
│   └── (images du site)
├── assets/
│   ├── tests-contrats/
│   ├── lighthouse/
│   └── (captures d’écrans et documents de validation)


💡 Objectifs du projet

✅ Proposer un site léger, rapide à charger et économe en ressources.

✅ Appliquer les bonnes pratiques d’éco-conception web.

✅ Offrir un bon niveau d’accessibilité (navigation clavier, contrastes, lisibilité).

✅ Être compatible mobile grâce à Bootstrap (cards, grid, responsive navbar).

✅ Présenter les services, horaires et formulaire de contact avec simplicité.


🛠️ Technologies utilisées

Outil	            Description

HTML5	            Structure sémantique, balisage accessible
CSS3	            Design minimaliste et performant
Bootstrap 5.3	    Grilles, cards, boutons et navbar responsive
Google Fonts	    Intégration de la police “Lobster Two”
Éco-conception	    Poids optimisé, lazy loading, structure épurée


🖼️ Pages disponibles
index.html : Page d'accueil, navigation, image principale (lazy-loaded)

programmes.html : Présentation des programmes 

contacts.html : Carte, horaires, formulaire de contact accessible


🪴 Éco-conception
Le site a été pensé pour minimiser son empreinte environnementale :

✅ Images WebP compressées et optimisées.

✅ Lazy loading systématique sur les images (loading="lazy").

✅ Pas de dépendances lourdes ou scripts inutiles.

✅ Feuilles de style condensées dans un seul fichier CSS.

✅ HTML structuré, sans redondance.

![Aperçu Lighthouse de la page d'accueil](./assets/Lighthouse%20index.png)
![Aperçu Lighthouse de la page programmes](./assets/Lighthouse%20programmes.png)
![Aperçu Lighthouse de la page de contacts](./assets/Lighthouse%20contacts.png)


♿ Accessibilité

Des efforts spécifiques ont été faits pour respecter les recommandations WCAG :

✅ Balises label correctement associées aux champs (for, id uniques).

✅ Contraste texte/fond vérifié.

✅ Navigation clavier fonctionnelle.

✅ Texte lisible avec des unités accessibles (em, rem).

En réalisant ces tests j'ai été amménée à faire des corrections au niveau des contrasts, retrouvables ci-dessous : 

![Aperçu du test de contrast pour #FBBD96 et #FFFFFF](./assets/Contrast%20h2%20avant%20correction.png)
![Aperçu du test de contrast pour #92572C et #FFFFFF](./assets/Contrast%20h2%20fond%20blanc%20correction.png)

![Aperçu du test de contrast pour #92572C et #F6AA7B](./assets/Contrast%20h2%20index%20avant%20correction%20png.png)
![Aperçu du test de contrast pour #4A2B17 et #F6AA7B](./assets/Contrast%20h2%20index%20correction.png)

![Aperçu du test de contrast pour #000000 et #FBBD96 ](./assets/Contrast%20black%20and%20pink%20navbar%20and%20footer.png)
![Aperçu du test de contrast pour #000000 et #0D6EFD](./assets/Contrast%20btn%20programmes.png)


📎 Voir /assets/tests-contrats/ pour les captures des validations.

🎨 Design & Bootstrap

Le design est épuré et s’adapte à tous les supports grâce à Bootstrap :

✅ Navbar responsive avec menu burger (checkbox + CSS personnalisé).

✅ Cards Bootstrap pour structurer les contenus (ex : programmes).

✅ Grille fluide et responsive (.container, .row, .col).

✅ Utilisation de boutons, formulaires, et classes utilitaires de Bootstrap.

📷 Captures & Tests

Les dossiers assets/ contiennent :

📸 Captures d’écran de Lighthouse (performance, SEO, accessibilité).

📑 Tests de contrats pédagogiques validant la conformité du projet.

🚀 Comment l’ouvrir localement

Clone le dépôt :

bash
Copier
Modifier
git clone https://github.com/votre-utilisateur/evenements-co.git
cd evenements-co
Ouvre index.html dans ton navigateur :

bash
Copier
Modifier
start index.html
Aucun serveur local requis. Toutes les ressources sont en local ou sur CDN.

🔒 Mentions légales et crédit
Site fictif réalisé dans le cadre d'un exercice pédagogique.

Création : m.zielinski.webdev@gmail.com

Technologies : HTML5, CSS3, Bootstrap, bonnes pratiques Green IT

✅ Améliorations possibles

Ajout de formulaire dynamique avec API (ex. Formspree ou PHP).

Intégration d’un outil comme Ecoindex pour mesure automatisée.

Version multilingue (FR/EN).

Ajout d’un mode sombre.

📬 Contact
Pour toute question ou amélioration :
📧 m.zielinski.webdev@gmail.com
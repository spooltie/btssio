# FICHE DE SITUATION PROFESSIONNELLE — BLOC 1 (ÉPREUVE E5)

## 1. IDENTIFICATION GÉNÉRALE
- **Titre de la réalisation :** Création de l'identité visuelle et du site vitrine de la marque ORA Energy
- **Cadre de réalisation :** [ ] Stage 1  [ ] Stage 2  [ ] Atelier de professionnalisation  [x] Projet de cours
- **Période de réalisation :** Décembre 2025 *(mise en ligne du code le 18/12/2025)*
- **Modalité :** [ ] Individuel  [x] En équipe (3 personnes : Benjamin Bastide, Yaëlle Pélerin, Mathéo Catalan)
- **Localisation / Organisation cliente :** Marque fictive ORA Energy (projet pédagogique)

## 2. CONTEXTE ET OBJECTIFS
- **Contexte organisationnel :** ORA Energy est une marque fictive de boisson énergisante naturelle, bio et française, positionnée comme une alternative saine aux boissons énergisantes classiques. La gamme compte trois saveurs : Émeraude, Ruby et Améthyste. La marque n'avait ni identité graphique ni présence en ligne.
- **Problématique / Besoin exprimé :** Donner à la marque une présence web cohérente avec son positionnement « énergie + naturel ». Le site doit présenter les produits, l'histoire de la marque et permettre une prise de contact.
- **Objectifs fixés :**
  - Concevoir de zéro la charte graphique (couleurs, typographies, logo).
  - Maquetter les 4 pages du site sur Figma : Accueil, Produits, Histoire, Contact.
  - Développer un site fidèle à la maquette, léger et responsive (bureau, tablette, mobile).
  - Publier le site en ligne.

## 3. DÉMARCHE ET ENVIRONNEMENT TECHNIQUE
- **Environnement technologique mobilisé :**
  - *Conception :* Figma (maquettes et système de design), Photoshop (visuels)
  - *Développement :* VS Code, HTML5, CSS3 (Flexbox, Grid, media queries), JavaScript natif, sans CMS ni framework
  - *Versionnement et hébergement :* Git / GitHub, publication via GitHub Pages
- **Démarche suivie étape par étape :**
  1. *Charte graphique :* Contraste noir / vert vif. Le noir évoque l'énergie nocturne, le vert le naturel et le bio. Une couleur d'accent est attribuée à chaque saveur. Palette : vert `#3EF081`, fond `#000000`, texte `#FFFFFF`, améthyste `#3D006C`, ruby `#FF0009`. Typographies : WIDESCREEN (titres), Lemon Milk (navigation et labels), New Astro (texte courant).
  2. *Maquettes Figma :* Les 4 pages ont été conçues en binôme avec la designer. J'ai pris en charge l'architecture des composants, les espacements, le système couleurs/typographies et les coins décoratifs en « L ».
  3. *Développement :* Intégration en HTML/CSS/JS purs pour rester au plus près de la maquette et garder un site léger (4 pages HTML, 4 feuilles de style, environ 3 200 lignes au total).
     - Barre de navigation fixe en Flexbox (logo à gauche, liens à droite).
     - Page Produits en CSS Grid sur trois colonnes (`repeat(3, 1fr)`).
     - Menu burger pour le mobile, en CSS pur (case à cocher `#menu-toggle` et sélecteur `:checked`) avec ouverture latérale.
     - Effets au survol : les cartes produits se soulèvent avec une ombre de la couleur de chaque saveur.
     - Éléments décoratifs en CSS sans images (coins en L, barre de défilement verte) et barre de progression de lecture en JavaScript.
     - Responsive avec des points de rupture à 767 px et 1 024 px.
     - Formulaire de contact avec champs obligatoires (`required`) et type `email` contrôlé par le navigateur.
  4. *Mise en ligne et vérification :* Dépôt du code sur GitHub, publication sur GitHub Pages, puis contrôle de l'affichage sur les trois formats d'écran.
- **Gestion des imprévus / Incidents rencontrés :** Manque d'investissement de certains membre du groupe ayant très peux de temps pour réaliser ce projet, provoquant une surcharge personnel pour rendre le projet dans les temps.

## 4. RÔLE ET CONTRIBUTION PERSONNELLE
- **Responsabilité précise :** Développeur web et co-designer. Responsable de toute l'intégration du site et co-auteur de la maquette.
- **Actions menées individuellement :**
  - Construction du système de design dans Figma (composants, espacements, couleurs, typographies).
  - Développement intégral des 4 pages en HTML/CSS/JS.
  - Mise en place du responsive et du menu burger mobile.
  - Gestion du dépôt GitHub et publication sur GitHub Pages.
- **Répartition dans l'équipe :** Benjamin Bastide (développement & design), Yaëlle Pélerin (design), Mathéo Catalan (marketing).

## 5. LIVRABLES ET PREUVES ASSOCIÉES
- Site en ligne : https://spooltie.github.io/OraEnergy/
- Code source versionné : https://github.com/spooltie/OraEnergy
- Page de présentation du projet : https://www.benjaminbastide.fr/ora-energy/
- Maquettes Figma des 4 pages, à exporter en images dans `preuves/Figma` : 
- Charte graphique (palette et typographies), à mettre dans `preuves/Charte Graphique` :
- Captures du site sur bureau, tablette et mobile, à mettre dans `preuves/Captures` :

## 6. COMPÉTENCES DU BLOC 1 MOBILISÉES
- [ ] **B1.1 — Gérer le patrimoine informatique**
- [ ] **B1.2 — Répondre aux incidents et demandes d'assistance**
- [x] **B1.3 — Développer la présence en ligne :** Création complète de la présence web d'une marque : charte graphique, site vitrine responsive aux normes HTML/CSS, mise en ligne (savoir S12).
- [x] **B1.4 — Travailler en mode projet :** Projet mené à trois avec des rôles répartis (design, développement, marketing), une phase de conception Figma avant le développement et un code versionné sous Git.
- [x] **B1.5 — Mettre à disposition des utilisateurs un service informatique :** Publication du site sur GitHub Pages et vérification de son fonctionnement sur différents terminaux.
- [x] **B1.6 — Organiser son développement professionnel**

## 7. BILAN RÉFLEXIF ET AUTO-ÉVALUATION
- **Points forts :** Site fidèle à la maquette, léger (aucun framework) et responsive sur trois formats. Identité visuelle cohérente du logo jusqu'aux effets de survol. Menu mobile réalisé sans JavaScript.
- **Axes d'amélioration :**
  - *Formulaire de contact :* il n'envoie rien pour l'instant (pas d'attribut `action`, pas de traitement côté serveur). À brancher sur un service d'envoi ou un script serveur, avec une mention d'information RGPD sur l'usage des données collectées.
  - *Référencement (SEO) :* ajouter une balise `<meta name="description">` sur chaque page et des textes `alt` plus descriptifs (par exemple, remplacer `alt="icone"`).
  - *Licences :* les polices WIDESCREEN utilisées sont des versions d'essai (*Trial*), qui ne sont pas autorisées pour une mise en ligne publique. Il faut acheter une licence ou choisir une police libre (Google Fonts).
  - *Mentions légales :* ajouter une page de mentions légales, obligatoire pour un site publié.
  - *Code :* factoriser le CSS commun à toutes les pages (en-tête, pied de page) pour éviter les répétitions.
- **Compétences professionnelles consolidées :** Passage d'une maquette à une intégration fidèle, mise en page CSS moderne (Flexbox, Grid, media queries), travail en équipe pluridisciplinaire, versionnement Git et publication d'un site.

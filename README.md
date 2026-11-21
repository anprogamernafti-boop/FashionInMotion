<div align="center">
  <img src="assets/logoFIM.jpg" alt="Logo officiel de Fashion In Motion" width="300">

  # Fashion In Motion

  ### L'élégance masculine, pensée pour le web.

  <p>
    Boutique de mode responsive avec catalogue, panier interactif et parcours de commande en ligne.
  </p>

  <p>
    <a href="https://fashioninmotion.tn"><strong>Voir la boutique en ligne</strong></a>
    ·
    <a href="https://github.com/anprogamernafti-boop/FashionInMotion"><strong>Explorer le code</strong></a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Interface-HTML%2C%20CSS%20%26%20JavaScript-111111?style=flat-square" alt="Interface HTML CSS JavaScript">
    <img src="https://img.shields.io/badge/Responsive-Mobile%20%26%20Desktop-c9a84c?style=flat-square" alt="Design responsive">
    <img src="https://img.shields.io/badge/Deployment-GitHub%20Pages-24292f?style=flat-square&logo=github" alt="Déploiement GitHub Pages">
  </p>
</div>

---

## L'expérience

**Fashion In Motion** est une expérience e-commerce front-end inspirée des codes de la maison de luxe : palette sombre, accents dorés, typographie éditoriale et navigation fluide.

Le parcours accompagne le visiteur de la découverte des collections jusqu'à la transmission de sa commande, tout en conservant une interface légère, élégante et adaptée aux écrans mobiles.

## Ce que propose la boutique

| Espace | Expérience |
| --- | --- |
| **Collections** | Univers Homme, Accessoires et Toute la collection pour explorer rapidement le catalogue. |
| **Boutique** | Produits, catégories, filtres et ajout au panier depuis une interface claire. |
| **Panier** | Quantités ajustables, suppression d'articles et calcul automatique du total. |
| **Commande** | Coordonnées client, informations de livraison et récapitulatif avant envoi. |
| **Éditorial** | Lookbook, savoir-faire, édition limitée, témoignages et univers de marque. |
| **Paiement à la livraison** | Parcours de commande avec notification au marchand et instructions D17. |

> **À propos du parcours D17** — l'interface permet de transmettre les informations de confirmation, mais la vérification du transfert reste manuelle côté marchand. Le site n'interroge pas directement une API bancaire.

## Une direction artistique premium

- Identité visuelle inspirée de la haute couture et du prêt-à-porter masculin.
- Préchargeur animé avec le logo officiel Fashion In Motion.
- Navigation sticky et responsive pour mobile, tablette et desktop.
- Sections éditoriales conçues pour raconter la marque au-delà du catalogue.
- Micro-interactions, transitions douces et retours visuels lors des actions du panier.
- Mise en page sans framework lourd ni étape de compilation.

## Technologies

- **HTML5** pour la structure sémantique de la boutique.
- **CSS3 intégré** pour le design, les animations et le responsive design.
- **JavaScript natif** pour le catalogue, les filtres, le panier et le parcours de commande.
- **Google Fonts** pour la direction typographique.
- **Font Awesome** pour les icônes d'interface.
- **FormSubmit** pour la transmission des formulaires de commande.
- **GitHub Pages** pour la publication.

## Lancer le projet en local

Prérequis : [Python 3](https://www.python.org/) installé.

```bash
git clone https://github.com/anprogamernafti-boop/FashionInMotion.git
cd FashionInMotion
python -m http.server 8000
```

Ouvrir ensuite [http://localhost:8000](http://localhost:8000) dans le navigateur.

Le projet est un site statique : aucune installation de dépendances et aucune étape de build ne sont nécessaires.

## Structure du dépôt

```text
FashionInMotion/
├── assets/
│   └── logoFIM.jpg     # Logo officiel de la marque
├── index.html          # Interface, styles et logique de la boutique
└── README.md           # Documentation du projet
```

## Configuration des commandes

Le formulaire utilise l'adresse FormSubmit configurée dans `index.html`. Avant de réutiliser le projet :

1. Remplacer le destinataire par une adresse que vous contrôlez.
2. Vérifier les informations affichées aux clients avant l'envoi.
3. Tester le parcours complet depuis le panier jusqu'à la réception du message.
4. Ne jamais publier de coordonnées bancaires ou d'informations de paiement personnelles dans le dépôt.

## Publication

La version en ligne est publiée automatiquement sur GitHub Pages :

**[fashioninmotion.tn](https://fashioninmotion.tn)**

## À propos

Projet personnel réalisé par **Asser Nafti**.

<div align="center">
  <br>
  <sub>Fashion In Motion · Luxe & Élégance</sub>
</div>

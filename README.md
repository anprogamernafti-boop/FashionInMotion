# Fashion In Motion

### Boutique de mode responsive avec panier et parcours de commande en ligne

<p align="center">
  <img src="assets/screenshots/home.jpg" alt="Page d’accueil de Fashion In Motion" width="820">
</p>

<p align="center">
  <a href="https://anprogamernafti-boop.github.io/FashionInMotion/">Voir Fashion In Motion</a> ·
  <a href="https://github.com/anprogamernafti-boop/FashionInMotion">Code source</a>
</p>

Fashion In Motion est une boutique front-end consacrée à la mode masculine et aux accessoires. Le parcours couvre la découverte des collections, la composition d’un panier et la transmission d’une commande avec les informations de livraison.

## Aperçu du catalogue

<p align="center">
  <img src="assets/screenshots/catalog.jpg" alt="Catalogue et filtres de Fashion In Motion" width="820">
</p>

## Fonctionnalités

- Catalogue de produits et filtres par collection.
- Panier interactif avec quantités et calcul du total.
- Formulaire de commande et informations de livraison.
- Commande à la livraison avec notification au marchand.
- Parcours D17 avec instructions de transfert et envoi des informations de confirmation au marchand.
- Sections éditoriales : collections, lookbook, savoir-faire, avis et contact.

**Le parcours D17 est opérationnel côté interface, mais la vérification du transfert est manuelle par le marchand.** Le site n’interroge pas directement une API bancaire.

## Technologies

| Domaine | Technologies |
| --- | --- |
| Interface | HTML, CSS intégré et JavaScript natif |
| Typographie et icônes | Google Fonts et Font Awesome |
| Notifications de commande | FormSubmit |
| Publication | GitHub Pages |

Le dépôt est un site statique : il n’a pas de serveur applicatif personnalisé ni d’étape de compilation.

## Lancer le site en local

Prérequis : Python 3 installé.

    git clone https://github.com/anprogamernafti-boop/FashionInMotion.git
    cd FashionInMotion
    python -m http.server 8000

Ouvre ensuite [http://localhost:8000](http://localhost:8000).

## Configuration des commandes

Les formulaires transmettent les détails de commande au destinataire FormSubmit configuré dans le code. Avant de réutiliser le projet, remplace ce destinataire par une adresse que tu contrôles et vérifie les informations de confidentialité affichées aux clients. Ne publie pas de coordonnées de paiement personnelles dans le dépôt.

## À propos

Projet personnel réalisé par Asser Nafti. Les captures présentées ci-dessus proviennent de la boutique publiée.

# Livrable

## Ce que tu dois faire

En partant de zéro

* Choisir ou proposer un sujet de projet
* Bien lire [le barème](BAREME.md) pour éviter les hors-sujets (**jusqu'à -8pts**)
* Choisir **2 à 6 exigences complémentaires** parmi celles proposées dans [le barème](BAREME.md)
* Créer un site web en respectant les **exigences essentielles** et les **exigences complémentaires** décrites
  ci-dessous.
* Préparer **une démo** où le groupe présentera le projet et **expliquera ses choix techniques**
* Répondre **individuellement** à quelques questions sur **sa contribution**, **le projet** et quelques **questions de cours**

## Exigences essentielles

Les exigences essentielles sont indispensables pour tous les projets.

Il faut toutes les implémenter pour obtenir le maximum de points.

### Structure HTML de base et validité du code

Pas **d'erreur** sur le [validateur HTML](https://validator.w3.org/) et
le [validateur CSS](https://jigsaw.w3.org/css-validator/ ) (les avertissements ne sont pas pris en
compte)

### Site Web

Le site comporte au moins 3 pages HTML distinctes et pertinentes

### Déploiement

Le site est accessible publiquement sur internet

### Pied de page

Un pied de page comporte des liens pointant vers le dépôt github du
projet, [la page Speedlify](https://coda-school.github.io/speedlify-dijon-b1-2025/) du projet

### Favicon

Icône de favoris

### Navigation du site

Une navigation en entête et/ou pied de page et des liens hypertexte permet de naviguer entre les différentes pages du
site Web

### Navigation interne

Pouvoir se déplacer d'un endroit à un autre de la même page sans que celle-ci soit rechargée

### Médias

Le site comporte au moins 5 images dont au moins 1 porteuse de sens, ils sont dimensionnés correctement et ont une
alternative textuelle si pertinent

### Le site est responsive et mobile first

Le site est conçu par défaut pour les petits terminaux. Le site s'affiche sans perte de contenu ou de fonctionnalité sur
un petit terminal (largeur d'écran : 320px), un terminal moyen (>320px), un grand terminal (>720px) ou avec un niveau de
zoom de 200%.

### Les liens externes sont identifiés par une icône

Les noms des liens externes (commençant par `http://` ou `https://` sont suffixés par un emoji "
🔗"                                                                                                                                                             |

### Applique un reset CSS

Un reset CSS permet d'unifier l'apparence sur les différents navigateurs et de déterminer le style par défaut de
certains éléments HTML.

## Exigences complémentaires

Chaque groupe peut choisir un certain nombre **d'exigences complémentaires** en début de projet.

**Entre 2 et 6** exigences complémentaires sont choisies parmi celles proposées [dans le barème](BAREME.md).

Elles doivent être reportées ci-dessous.

### Exigence 1

### Exigence 2


## Rendu attendu

* Un **site web statique** dont le code source et les ressources se trouvent dans le dossier [`public`](public)
* Le site web est **disponible publiquement** sur les **pages Github**
* Des **éléments de documentation** permettent à quelqu'un qui débarque dans le projet de démarrer rapidement ([
  `docs`](docs))
* Les résultats [d'analyse Lighthouse via Speedlify](https://coda-school.github.io/speedlify-dijon-b1-2025/) déterminent
  un score global pour l'accessibilité, les bonnes pratiques, la performance, la SEO
* Lors de la démo, le groupe présente son projet, **explique ses choix** et participe **à une revue de code**
* Lors de la démo, chaque membre répond **individuellement** à des questions sur **ses contributions**, sur **le projet** et à des **questions de cours**
* Le site doit pouvoir **se lancer localement** après avoir été fraichement cloné via la commande suivante :

```shell
npx vite public
# ou si la commande vite est installée globablement
vite public
```
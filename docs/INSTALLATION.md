# Démarrage de site statique simple

Le code source du site situé dans le dossier `public` est déployé automatiquement sur les Github Pages lorsque du code est commit ET poussé sur le dépôt.

## Déploiement sur Github pages

Le dépôt doit avoir la visibilité `public`

Dans les `paramètres` du dépôt, rubrique `Pages`, s'assurer que la source de déploiement est positionnée à `Github Actions`.

## Afficher le lien de la page dans Github

Revenir à la page principale du dépôt Github.

Dans la rubrique `à propos` (à droite), passer en mode edition.

Dans la rubrique site Web, cocher `Utiliser votre site Web Github Pages`.

Sauvegarder les changements.

L'adresse du site est maintenant affichée dans la rubrique `à propos`.

## Lancer le serveur en local avec vite

Après avoir rempli les prérequis (voir plus bas).

Dans une ligne de commande:
```shell
npx vite public
```

Ou si vous avez installé la CLI `vite` globalement
```shell
vite public
```

Ouvrir dans le navigateur : http://localhost:5173

## Prérequis

### Installer nodejs

Installer nodejs : https://nodejs.org/fr/download

### (Optionnel) installer vite globalement

Installer la commande `vite`

Dans une ligne de commande:
```shell
npm install -g vite
```


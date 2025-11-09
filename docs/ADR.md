# ADR 

Journal des décisions d'architecture.

<!-- 
Datez et nommez les décisions techniques significatives dans votre projet
Expliquez le contexte amenant à cette décision.
Les alternatives considérées ainsi que le choix retenu et les raisons pour lesquelles ce choix a été fait.

Voici un premier exemple 👇
-->

## 01 - Déploiement du site statique sur Github pages

Le 2025-11-09

**Contexte**

Le code des projets est versionné sur Github car c'est aujourd'hui l'outil utilisé à l'école Coda par tous les étudiants. 

Nous souhaitons **déployer publiquement** les sites des projets de groupes pour pouvoir **bénéficier d'outils pour analyser la qualité** des sites web. Ainsi, les étudiant-es pourront **détecter les problèmes** de qualité et **apprendre à les corriger**.

**Alternatives considérées**

- Les étudiants déploient le site localement avec [Vite](https://vite.dev/)
- Utilisation de [Netlify](https://www.netlify.com/)
- Utilisation des [Github Pages](https://docs.github.com/fr/pages)

**Choix retenu : Github Pages**

Github Pages est très bien intégré à Github. Cela ne nécessite pas de dépendre à un service supplémentaire ou à des droits particuliers (comme Netlify le nécessiterait). L'option de déploiement local avec Vite n'a pas été retenue car il serait très compliqué de mettre en place les outils de monitoring, ce qui dépendrait d'avoir la machine d'un-e étudiant-e allumée quand les outils de monitoring seraient actifs.

## 02 - <!-- Remplacez ce commentaire par le titre d'une de vos décisions --> 


Le <!-- date de la décision -->

**Contexte**

<!-- 
Contexte qui a amené à prendre la décision. Les forces en présence, les contraintes.
-->

**Alternatives considérées**

<!-- 
Listez au moins 2 options avec des liens pour pouvoir les retrouver
-->

**Choix retenu : <!-- Remplacer ce commentaire par l'option choisie -->**

<!-- 
Expliquez pourquoi vous avez retenu l'option. 
En quoi elle est plus adaptée aux autres options.
Pourquoi les autres options ne sont pas adaptées
-->
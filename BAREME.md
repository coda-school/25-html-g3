# Barème de notation ( /20 )

1. **Le code est commit et poussé régulièrement sur Github** – **1 pt**
    * La [page de monitoring](https://coda-school.github.io/speedlify-dijon-b1-2025/) montre des variations régulière
      des métrique
    * Il y a des commits réguliers sur Github
2. **Le site respecte les exigences essentielles** - **8 pts**
3. **Le site respecte les exigences complémentaires** - **4 pts**
4. **Score global Lighthouse** – **2 pts**
    * `score < 200` => 0pts
    * `200 <= score < 300` => 1pt
    * `300 <= score < 400` => 2pts
    * Vous pouvez choisir une exigence complémentaire pour obtenir 1pts supplémentaire si vous pensez pouvoir obtenir un
      score de 400
5. **Modularité et simplicité** – **2 pts**
    * Les classes CSS et sélecteurs superflux sont évités
    * Les duplications sont réduites quand possible
    * La cascade, les priorités et l'héritage sont utilisés à bon escient
6. **Evaluation individuelle** – **3 pts**
    * Au moins 1 commit qualitatif par jour par individu
    * Lors de la démo, l'apprenant-e peut expliquer ses contributions
    * Il/elle peut répondre à quelques questions sur le projet et sur le cours.
7. **Respect de l'énoncé** - (**<span style="color:red">entre 0pts et -8pts retranchés</span>** du total si pas respectées)
    * Pas de Javascript
    * Partir de 0. Ne pas utiliser de travail pré-existant.
    * Utilisation d'IA ou d'extraits de code extérieur autorisés à condition qu'il soit remanié, simplifié et adapté au
      contexte du projet

## Respect de l'énoncé et Hors-sujet

Ci-dessous, le détail des contraintes du projet.
Leur **non-respect** entrainera **retraits de points cumulables** qui seront appliqués **après le décompte** des points.

Ex. si vous avez 20/20 et un malus de -5pts, votre note finale sera 15/20.

| Contraintes du projet                                                                                                                       | Modificateur de points                                           |
|---------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------|
| **Ne pas utiliser Javascript** (la présence de code javascript vous pénalisera)                                                             | -3pts si JS présent, +0pts sinon                                 |
| Il faut **partir de 0**. Ne pas utiliser de travail pré-existant. Pénalité si **beaucoup de code apparait d'un coup** en très peu de temps. | -3pts si beaucoup de code apparait d'un coup +0pts sinon         |
| Pas de copier-collé de code extérieur ou de l'IA  **sans adaptation au contexte ni revue ni remaniement**                                   | -2pts si quantité importante de code généré détecté, +0pts sinon |

> **A propos de l'IA** (et du copier-coller venant de l'extérieur).
>
> Je **n'interdis pas** l'utilisation de l'IA ni l'inspiration de code venant de l'extérieur.
> Je pénaliserai la présence de code qui n'aura **pas été adapté à votre contexte** (ex. code inutile ou "au cas où",
> conventions de nommage
> incohérentes, beaucoup de fonctionnalités ou de code d'un coup)

Le **partage et la réutilisation** de code n'est pas interdit **entre groupes de projets**.
Pour qu'il soit accepté, **attribuez** et/ou donnez **votre accord pour réutilisation** en suivant la démarche décrite
dans le fichier [`CREDITS.md`](CREDITS.md).

## Esthétique et interactivité

> **La qualité esthétique** (si c'est joli ou pas) **n'impactera pas** votre évaluation.
> Vous pouvez faire le site le plus moche que vous voulez à partir du moment où les critères ci-dessous sont respectés.

> **L'interactivité** (sauf si elle est possible sans javascript) n'est **pas demandée** (par exemple, si vous faites un
> projet
> de tier-list, il ne vous sera pas demandé d'implémenter le drag-and-drop)

> Rappelez-vous que comme pour tout projet, **la définition du problème** est au moins aussi importante que le code.
> En cas de doute, demandez au client (l'enseignant) pour vous assurer que vous avez bien compris son besoin.
> Rappelez-vous aussi que **le client peut changer d'avis** et que c'est **négociable**.

## Démo

Une session de démo (présentation du produit **dans son état courant**) se déroulera **le 3ème jour** (le jeudi 13
novembre) à partir du matin. Ceci pour s'assurer que le temps ne manquera pas.

**LE SITE N'A PAS BESOIN D'ETRE FINI POUR LA DÉMO**

> La démo permettra de demander et recevoir du feedback et d'expliquer les choix techniques qui auront été faits
> **jusque là**. Après la démo, l'équipe peut continuer d'améliorer son produit.

**N'attendez pas la démo pour demander un retour à l'enseignant ou autres autres groupes de projet**

## Exigences essentielles

Barème : 8pts

**L'ensemble** de ces exigences doit être pris en compte pour obtenir le maximum de points.

| Exigences                                        | Critère d'acceptation                                                                                                                                                                                                                                           | Barème  |
|--------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------|
| Structure HTML de base et validité du code       | Pas **d'erreur** sur le [validateur HTML](https://validator.w3.org/) et le [validateur CSS](https://jigsaw.w3.org/css-validator/ ) (les avertissements ne sont pas pris en compte)                                                                              | 2pts    | 
| Site Web                                         | Le site comporte au moins 3 pages HTML distinctes et pertinentes                                                                                                                                                                                                | 0,5pts  | 
| Déploiement                                      | Le site est accessible publiquement sur internet                                                                                                                                                                                                                | 0,5pts  | 
| Pied de page                                     | Un pied de page comporte des liens pointant vers le dépôt github du projet, [la page Speedlify](https://coda-school.github.io/speedlify-dijon-b1-2025/) du projet                                                                                               | 0,25pts | 
| Favicon                                          | Icône de favoris                                                                                                                                                                                                                                                | 0,25pts | 
| Navigation du site                               | Une navigation en entête et/ou pied de page et des liens hypertexte permet de naviguer entre les différentes pages du site Web                                                                                                                                  | 0,5pts  | 
| Navigation interne                               | Pouvoir se déplacer d'un endroit à un autre de la même page sans que celle-ci soit rechargée                                                                                                                                                                    | 0,5pts  | 
| Médias                                           | Le site comporte au moins 5 images dont au moins 1 porteuse de sens, ils sont dimensionnés correctement et ont une alternative textuelle si pertinent                                                                                                           | 0,5pts  | 
| Le site est responsive et mobile first           | Le site est conçu par défaut pour les petits terminaux. Le site s'affiche sans perte de contenu ou de fonctionnalité sur un petit terminal (largeur d'écran : 320px), un terminal moyen (>320px), un grand terminal (>720px) ou avec un niveau de zoom de 200%. | 2pts    | 
| Les liens externes sont identifiés par une icône | Les noms des liens externes (commençant par `http://` ou `https://` sont suffixés par un emoji "🔗"                                                                                                                                                             | 0,5pts  | 
| Applique un reset CSS                            | Un reset CSS permet d'unifier l'apparence sur les différents navigateurs et de déterminer le style par défaut de certains éléments HTML.                                                                                                                        | 0,5pts  | 

## Exigences complémentaires

Barème : 4 pts max (absence de l'exigence : 0pt, puis barème de chaque exigence jusqu'au plafond de 4pts)

Choisir **entre 2 à 6** exigences complémentaires parmi les suivantes :

| Exigence                                                          | Critère d'acceptation                                                                                                                                                                                                                                                                                                                                       | Barème              |
|-------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------|
| Mode sombre/clair                                                 | Le site dispose d'un mode sombre/clair en fonction des préférences du système d'exploitation                                                                                                                                                                                                                                                                | 1pt                 |
| Feuille de style d'impression                                     | Le site dispose d'une feuille de style optimisée pour l'impression. Economie d'encre, pagination, sauts de page, police de caractères sont à considérer.                                                                                                                                                                                                    | 1pt                 |
| Les paramètres de contraste sont optimisés                        | Le site dispose de directives CSS permettant d'adapter les styles aux préférences de contraste du système d'exploitation                                                                                                                                                                                                                                    | 1pt                 |
| Formulaire de contact avec style                                  | Le site dispose d'un formulaire de contact dont le style s'adapte à l'état des champs de saisie                                                                                                                                                                                                                                                             | 1pt                 |
| Navigation sticky et burger menu pour mobile sans javascript      | Lorsqu'on scrolle verticalement, le menu de navigation reste affiché en haut de la page. Si la largeur du terminal est en dessous de 512px, le menu de navigation et remplacé par un bouton permettant de déplier/replier le menu. Tu as le droit de trouver une solution à l'extérieur, mais sois prêt-e à pouvoir expliquer le fonctionnement de ton code | 2pts                |
| Les images sont téléchargées en s'adaptant au terminal/navigateur | Des images différentes sont téléchargées en fonction du terminal ou du navigateur                                                                                                                                                                                                                                                                           | 1pt                 |
| Challenge Lighthouse 100 - 100 - 100 - 100                        | Avec un contenu pertinent, atteindre au moins une fois le score de 400 pts sur Lighthouse sur les 10 dernières mesures speedlify (ne peut pas être cumulé avec l'exigence "Ecoindex")                                                                                                                                                                       | 1pt                 |
| Version bilingue                                                  | Traduire le site dans une autre langue et proposer un lien pour passer d'une version à l'autre. C'est un challenge qui mettra à l'épreuve la communication et la coopération en équipe.                                                                                                                                                                     | 2.5pts              |
| Ecoindex                                                          | Avec un contenu pertinent, obtenir un bon score d'Ecoindex (https://www.ecoindex.fr/). (ne peut pas être cumulé avec l'exigence "Lighthouse 100 - 100 - 100 - 100")                                                                                                                                                                                         | B = 0,5pts, A = 1pt |
| Utilise une convention CSS dans le projet                         | Choisis une convention CSS (ex. [BEM](https://getbem.com/), ). Sois-prêt-e à le justifier et expliquer comment tu l'as mis en place.                                                                                                                                                                                                                        | 2.5pts              |



# TODO
## Étape 1 : Mettez en place votre environnement de développement

### 🪴 Avant de démarrer cette étape, je dois avoir :

- [x] Suivi les parties 1 et 2 du cours “Gérez votre code avec Git et GitHub”.
- [x] Suivi le cours "Simplifiez-vous le CSS avec SASS” si vous souhaitez utiliser
SASS.

### 🎯 Une fois cette étape terminée, je dois avoir :

- [x] Mon projet sur un repo GitHub.
- [x] Une structure de projet contenant :
  - [x] une page index.html ;
  - [x] un dossier pour les assets (fichier CSS, images) ;
  - [x] un dossier pour le SASS (optionnel) ;
  - [x] un dossier ‘restaurants’ pour y mettre les pages de restaurants.

### 📌 Recommandations :

- [x] Après avoir créé le dossier du projet, créez le fichier “ReadMe.md” avec le
nom du projet.
- [x] Initialisez le projet avec Git, et publiez le repo sur GitHub.
- [ ] Créez les différents fichiers nécessaires pour le projet.
- [x] Publiez le site sur GitHub Pages.
- [x] Si vous utilisez SASS, pensez à mettre en place une architecture 7:1 pour
garder de bonnes pratiques de développement.

### 🚨 Points de vigilance :

- [ ] Assurez-vous que le repo GitHub soit public pour que votre mentor ait
bien accès au projet.

### 📚 Ressources :

- [ ] Site de GitHub Pages
- [ ] Pour aller plus loin sur l’utilisation de Git et GitHub, suivez le cours Devenez
un expert de Git et GitHub

## Étape 2 : Intégrez la version mobile de la page d’accueil

### 🪴 Avant de démarrer cette étape, je dois avoir :

Analysé les maquettes afin d’en identifier :
- [ ] les différentes couleurs utilisées sur le site ;
- [ ] les différentes sections de la page ;
- [ ] les différents composants (ce sont les éléments de l’interface qui
se répètent).

### 🎯 Une fois cette étape terminée, je dois avoir :

- [ ] La page d’accueil du site sans les animations.

### 📌 Recommandations :

- [ ] Pensez à analyser la maquette desktop de la page également, afin d’avoir une
meilleure idée de la gestion des sections.
- [ ] À chaque étape, pensez à vérifier votre code aux validateurs HTML et CSS. Vous
pouvez le faire en passant votre lien GitHub Pages au validateur.

### 🚨 Points de vigilance :

- [ ] Pensez bien que l’on souhaite ici faire une intégration Mobile First, c'est-à-dire
que le CSS principal nous servira pour le mobile, et que les media queries nous
permettront d’aller vers le format desktop.

### 📚 Ressources :

https://www.ionos.fr/digitalguide/sites-internet/web-design/mobile-first-la-nouvelle-approche-du-web-design/

# Étape 3 : Ajoutez les animations à la page d’accueil

### 🪴 Avant de démarrer cette étape, je dois avoir :

Suivi le cours “Créez des animations CSS modernes”.

### 🎯 Une fois cette étape terminée, je dois avoir :

- [ ] La page d’accueil avec les animations fonctionnelles pour la version
mobile.
- [ ] Les animations qui doivent s’intégrer de manière naturelle : si j’ai une
animation au survol d’un élément, alors j’ai l’animation dans le sens
contraire lorsque je quitte l’élément.

### 📌 Recommandations :

- [ ] Pour chaque création d’animation, vérifiez si un exemple précis à suivre est
donné. Si ce n’est pas le cas, demandez-vous : “Est-ce que mon animation
s’intègre bien avec le reste des animations du site ?”.

### 🚨 Points de vigilance :

- [ ] Pour une meilleure expérience utilisateur, il est important de prendre en
compte l’animation dans tous les états de ses composants. Par exemple : si on a
une animation au survol d’un élément, on doit avoir l’animation inverse lorsque
le curseur quitte l’élément.

### 📚 Ressources :

- [ ] Mozilla.org : Utiliser les transitions CSS
- [ ] MDN : Utiliser les animations CSS

# Étape 4 : Réalisez le responsive de la page d’accueil

### 🪴 Avant de démarrer cette étape, je dois avoir :
- [ ] Analysé la version desktop de la page d’accueil.
### 🎯 Une fois cette étape terminée, je dois avoir :
- [ ] La page d’accueil finalisée et publiée sur GitHub Pages.
### 📌 Recommandations :
- [ ] Identifiez des break points* standard dans votre application afin d’éviter
de multiplier les media queries.
### 🚨 Points de vigilance :
- [ ] Gardez en tête que pour la réalisation du responsive d’un site, il ne faut
ajouter que les règles que nous souhaitons modifier dans les media
queries.
### 📚 Ressources :

https://www.eficiens.com/cest-quoi-un-breakpoint/

# Étape 5 : Intégrez le HTML et le CSS d’une page de restaurant

### 🪴 Avant de démarrer cette étape, je dois avoir :
- [ ] Analysé la maquette des restaurants sur mobile et sur desktop.
### 🎯 Une fois cette étape terminée, je dois avoir :
- [ ] Une page de restaurant intégrée.
- [ ] La page validée au W3C pour le HTML et le CSS.
### 📌 Recommandations :
- [ ] Ici, vous devez suivre le même processus développé des étapes 2 à 4,
mais cette fois-ci sur la page du premier restaurant.

### 🚨 Points de vigilance :

- [ ] N’oubliez pas l’ellipse sur le nom et la description de plats qui sont trop
longs en version mobile.
- [ ] Faites attention aux rendus des animations. Assurez-vous qu’elles sont
conformes aux attentes du cahier des charges.

# Étape 6 : Copiez la page de restaurant et adaptez le contenu aux restaurants restants

### 🪴 Avant de démarrer cette étape, je dois avoir :
- [ ] Terminé d’intégrer la page du premier restaurant.
### 🎯 Une fois cette étape terminée, je dois avoir :
- [ ] Toutes les pages du site intégrées dans tous les formats.
### 📌 Recommandations :
- [ ] D’un restaurant à un autre, la structure reste la même, seul le contenu
change. Vous ne devriez donc pas avoir besoin de toucher au code CSS ni
à la structure du HTML, mais simplement de remplacer le contenu
(image + textes)

### 🚨 Points de vigilance :

- [ ] Après avoir intégré le contenu d’un nouveau restaurant, si vous avez
changé du CSS, assurez-vous que le restaurant original ne soit pas
impacté.
- [ ] Par ailleurs, ne dupliquez pas de code CSS inutilement. Les différentes
pages "restaurant" ont exactement la même forme et partagent donc le
même code CSS à l'exception de la bannière.

# Étape 7 : Faites une revue complète du projet

### 🪴 Avant de démarrer cette étape, je dois avoir :
- [ ] Terminé l’intégration des maquettes.
### 🎯 Une fois cette étape terminée, je dois avoir :
- [ ] Le projet finalisé et les livrables vérifiés.
### 📌 Recommandations :
- [ ] Prenez le temps de passer chaque page au validateur afin de vérifier que
le code est conforme aux attentes.
- [ ] Vérifiez le rendu sur mobile, tablette et desktop afin de vous assurer du
rendu. Celui-ci doit respecter le visuel des maquette

# Étape optionnelle : Réalisez une veille

> Pour ce projet, on vous a demandé de réaliser des animations exclusivement avec
> du code CSS. Si OhMyFood souhaite plus tard intégrer du JavaScript au projet, que
> conseillerez-vous ?
>Pour aller plus loin, nous vous invitons ici à chercher des informations sur la
> réalisation d’animations dans l’interface du site avec JavaScript.
> Cette veille permettra d’alimenter votre réflexion et sur le long terme, de vous rendre
> plus agile au changement. Une qualité incontournable chez un développeur !

# Projet terminé !

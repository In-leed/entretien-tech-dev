# Entretien technique developpeur web / web mobile<!-- omit in toc -->

## Table des matières<!-- omit in toc -->

- [Objectif](#objectif)
- [Déroulement](#déroulement)
- [Exercice](#exercice)
  - [Contraintes](#contraintes)
  - [Assets](#assets)
  - [Critères d'évaluation](#critères-dévaluation)
  - [Livraison](#livraison)

## Objectif

L'objectif de cet entretien est de nous permettre de mieux vous connaître, de comprendre vos compétences et de voir comment vous abordez un problème simple de développement.

On ne cherche pas à vous piéger, mais à échanger avec vous sur votre parcours, vos expériences et vos compétences.

⚠️ Ce test n'a pas pour vocation d'être fini dans le temps imparti, il est là pour évaluer votre manière de travailler, votre logique et vos compétences en développement web. ⚠️

## Déroulement

L'entretien se déroulera en trois parties :

1. Un échange autour de votre parcours, de vos expériences et de vos compétences.
2. Un exercice de développement.
3. Un échange autour de l'exercice réalisé et des questions sur le développement web en général.

## Exercice

L'exercice consiste à développer une landing page responsive en utilisant PHP, HTML, CSS et JavaScript.
Cette landing page doit contenir les éléments suivants :

- [ ] Un titre
- [ ] Un sous-titre
- [ ] Un affichage de produits avec les éléments suivants :

  - [ ] Une image
  - [ ] Un titre
  - [ ] Une description
  - [ ] Un prix

- [ ] Un formulaire d'avis avec les champs suivants :

  - [ ] Nom
  - [ ] Prénom
  - [ ] Note
  - [ ] Message
  - [ ] Un bouton de soumission du formulaire

- [ ] Un affichage des messages des utilisateurs avec les éléments suivants :
  - [ ] Nom
  - [ ] Prénom
  - [ ] Message

### Contraintes

- Vous ne pouvez pas utiliser de framework CSS (Bootstrap, Tailwind, etc.).
- Vous ne pouvez pas utiliser de bibliothèque JavaScript (jQuery, etc.).
- Vous avez à disposition une base de données SQL contenant les produits à afficher et les messages des utilisateurs.
- Vous pouvez utiliser le serveur PHP Laragon pour récupérer les données de la base de données (une introduction à Laragon vous sera faite si vous ne le connaissez pas).
- Vous avez maximum 3 heures pour réaliser l'exercice.

### Assets

Voici le lien de la maquette à respecter : [Lien de la maquette](https://www.figma.com/design/t20Lrn7kK1MfU9pD2qmKC4/Test-d%C3%A9veloppeurs?node-id=0-1&t=LFqRlvJbxszEyiKa-1) (vous devrez peut être vous connecter à Figma pour y accéder).

Vous trouverez dans le dossier `assets` les images des produits à afficher ainsi que le fichier SQL contenant les données à importer dans votre base de données.

### Critères d'évaluation

Total : 20 points

- Respect des consignes (et maquette) / 5

  - Navigation / 1
  - Couleurs et typographie / 1
  - Structure (navbar, footer, etc.) / 2
  - Qualité de l'intégration / 1

- Propreté du code / 3

  - Structure du projet / 1
  - Qualité du code / 2

- Features / 5

  - Affichage des produits / 2
  - Formulaire d'avis / 2
  - Affichage des avis / 1

- Sécurité / 3

  - Front : Echapement des données / 1.5
  - Back : Protection contre les injections SQL / 1.5

- Utilisation propre de Github : 2

  - Savoir utiliser les branches et les forks / 1
  - Nous ajouter en collaborateur / 1

- Touche perso / 2
  - Originalité / 1
  - Créativité / 1

### Livraison

Vous devrez fork ce dépôt Git, réaliser l'exercice dans une branche dédiée et nous ajouter en collaborateur (pseudo GitHub: InleedDev) sur votre dépôt et nous envoyer le lien une fois l'exercice terminé.

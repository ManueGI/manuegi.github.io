---
title: Secret Santa
publishDate: 2019-10-02 00:00:00
img: /assets/santa.png
img_alt: Couverture du site Secret Santa
vid: 'https://www.youtube.com/embed/awjF_DYKBCU?si=WaqpIXT19iZFVUcX'
description: Tirage au sort pour organiser son secret santa

tags:
  - Tirage aléatoire
  - Fullstack
  - Projet personnel
---

<a href="https://github.com/ManueGI/nain-porte-quoi.git"> Répertoire GitHub</a>

### Secret Santa

Bienvenue sur "Secret Santa", un site que j'ai développé en totale autonomie. Il sert à simplifier l'organisation d'échanges de cadeaux. Les utilisateurs peuvent créer des listes de membres inscrits sur le site, puis initier un tirage au sort automatique qui attribuera un donneur et un receveur à chacun. Chaque utilisateur dispose d'une page personnelle, permettant de partager leur wishlist. Cette plateforme vise à rendre l'expérience de "Secret Santa" aussi fluide que possible, en offrant un moyen simple et convivial de célébrer les fêtes entre amis, famille ou collègues.

> Architecture :

<strong>Backend - Ruby on Rails :</strong>
<ul>
  <li>Utilisation de Ruby on Rails pour la construction de l'infrastructure back-end</li>
  <li>Création du modèle "User" avec la gem Devise</li>
  <li>Gestion des autorisations avec la gem "Pundit"</li>
  <li>Mise en place de modèles tels que "User", "Group", "GroupMember", et "SantaAssignment".</li>
  <li>Création du modèle "Wihlist" pour servir de table de jointure entre les modèles "User" et "Wish" pour permettre une évolution au site internet. Le site peut évoluer et laisser la possibilité aux utilisateurs de créer plusieurs wishlists, par budget ou par type de cadeau par exemple</li>
</ul>

<strong>Frontend - Stimulus :</strong>
<ul>
  <li>Utilisation de bootstrap couplé à des composants SCSS personnalisés</li>
  <li>Utilisation de la gem "simple_form" pour les formulaires</li>
</ul>

> Compétences Acquises :

<strong>Hard Skills :</strong>
<ul>
  <li>Développement d'une application complète en Ruby on Rails</li>
  <li>Gestion des Relations : Création de relations sophistiquées entre les modèles pour assurer une structure de données efficace.</li>
</ul>

<strong>Soft Skills :</strong>
<ul>
  <li>Autonomie: recherche en autonomie de nouvelles fonctionnalités et de comment les mettre en Œuvre</li>
</ul>

> Résultats et perspectives :

La réalisation du projet "Secret Santa" en totale autonomie a été une expérience formatrice, consolidant mes connaissances existantes tout en m'offrant l'occasion de développer de nouvelles fonctionnalités de manière indépendante. La gestion du projet en solo m'a permis de prendre des décisions éclairées à chaque étape du processus de développement, renforçant ma confiance en tant que développeuse autonome. Forte de cette expérience, je suis impatiente de continuer à explorer des projets individuels et collaboratifs tout en restant engagée dans un apprentissage continu pour élargir mes compétences en développement web.
Si vous le souhaitez, vous pouvez explorer le code source sur le <a href="https://github.com/ManueGI/secret_santa.git"> répertoire GitHub</a> dédié au projet "Nain Porte Quoi".

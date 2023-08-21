---
title: Application de rappels d’événements
publishDate: 2023-03-23 00:00:00
img: /public/assets/stock-3.jpg
img_alt: Screen du projet
description: |
  Application Web permettant d'ajouter des événements sur une carte
tags:
  - Mapbox
  - JS objet
---

L’application permet à l’utilisateur de gérer des événements locaux ( fêtes,concerts, etc.).
Elle occupe tout l’écran et se compose d’une carte Mapbox et d’un panneau latéral à droite de la carte qui contient un formulaire de saisie.Ce formulaire sert à créer des événements locaux selon les spécifications suivantes:
Titre de l'événement,
Description de l'événement,
Dates de début et de fin,
Coordonnées géographiques.
Fonctionnalités: Au clic sur la carte les coordonnées sont alimentés,
Les événements s’affichent sur la carte sous forme de Markers,
Au survol de la souris sur un Marker on voit le titre et les dates de l’événement,Une Popup liée à chaque Marker affiche toutes les informations sur l’événement.

La punaise de l’événement est différente en fonction de la date, Verte: Événement dans plus de 3 jours, Orange: Événement dans 3 jours ou moins, Rouge: Événement dépassé. Un bouton de mise à jour des informations sous forme de contrôle personnalisé Mapbox est disponible en haut à gauche de la carte.

Les rappels sont enregistrés dans le localStorage. Au démarrage de l’application les rappels déjà enregistrés apparaissent sur la carte.

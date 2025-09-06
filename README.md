# Projet-BDD
Version statique du mini-projet BDD

Il s’agit d’une version statique du mini-projet BDD, réalisée uniquement avec HTML, CSS et JavaScript, car GitHub Pages ne prend pas en charge les langages côté serveur tels que PHP, Ruby ou Python.

Pour simuler une page dynamique, nous avons créé plusieurs pages statiques pour chaque utilisateur (une page de détail et une page de modification). Ces pages sont reliées entre elles, par exemple :
detail_arn.html ⇔ modif_arn.html.

La page index permet de tester si l’entrée correspond à un pseudonyme. Si oui, elle redirige automatiquement vers la page correspondante (du type detail_ + pseudo + .html), ce qui imite une recherche dynamique.

Inconvénient :

Impossible de modifier les données.

L’ajout d’un nouvel utilisateur demande plus de travail, car il faut créer une nouvelle page complète.

Objectif du projet :

Tester la mise en page sur différents appareils.

Observer comment l’interface s’adapte d’un écran à un autre.

Le rendre facilement accessible en ligne pour l’équipe, voire le partager au grand public.

Remarques

La page index.html correspond à formepage.php dans le projet d’origine.

Un bouton Liste a été ajouté dans index afin d’accéder à list.html (qui affiche tous les pseudos, avec possibilité de cliquer pour voir les détails).
👉 Dans le projet original, cette fonctionnalité était disponible via la page WAMP.

📌 Ce projet a été réalisé par le Groupe 1 des étudiants de l’UMMTO.

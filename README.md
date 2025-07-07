# Libft: Votre Toute Première Bibliothèque C 📚

## Introduction

Bienvenue dans Libft ! 🚀 Ce projet est votre première incursion dans la création d'une bibliothèque en C. Vous allez réimplémenter de nombreuses fonctions standard de la libc, ainsi que d'autres fonctions utiles, pour bâtir une collection d'outils polyvalents. C'est une étape fondamentale pour comprendre comment ces fonctions fonctionnent en interne et pour les utiliser efficacement dans vos futurs projets.

## Objectifs

L'objectif principal est de développer votre propre bibliothèque statique, libft.a, qui sera un atout précieux pour tous vos projets en C.

## Partie Obligatoire

La partie obligatoire de Libft est divisée en plusieurs sections :

libft.a 

    Nom du programme : libft.a 

Fichiers à rendre : Makefile, libft.h, ft_*.c 

Règles Makefile : NAME, all, clean, fclean, re 

Fonctions externes autorisées : Détaillées dans le sujet (principalement malloc, free, write).

Description : Créer votre propre bibliothèque, une collection de fonctions qui vous sera utile tout au long de votre cursus.

## Considérations Techniques 

    Interdiction stricte des variables globales. 

Les fonctions d'aide (helper functions) doivent être statiques pour limiter leur portée au fichier approprié. 

Tous les fichiers doivent être à la racine de votre dépôt. 

La soumission de fichiers inutilisés n'est pas autorisée. 

Chaque fichier .c doit compiler avec les drapeaux : -Wall -Wextra -Werror. 

Vous devez utiliser la commande ar pour créer votre bibliothèque. L'utilisation de libtool est strictement interdite. 

Votre libft.a doit être créée à la racine de votre dépôt. 

## Partie 1: Fonctions de la Libc 

Vous devez réimplémenter un ensemble de fonctions de la bibliothèque standard C (libc).


## Partie 2: Fonctions Additionnelles 

Vous devrez également implémenter des fonctions utilitaires supplémentaires qui ne font pas partie de la libc mais sont très pratiques. 

## Règles Communes 🤝

    Votre projet doit être écrit en C. 

Votre code doit être conforme à la Norme. Les fichiers ou fonctions bonus sont inclus dans la vérification de la norme, et toute erreur de norme entraînera une note de 0 pour le projet. 

Vos fonctions ne doivent pas se terminer de manière inattendue (segmentation fault, bus error, double free, etc.), sauf en cas de comportement indéfini. Si cela se produit, votre projet sera considéré comme non fonctionnel et recevra un 0. 

Toute mémoire allouée sur le 

heap doit être correctement libérée ; aucune fuite de mémoire ne sera tolérée. 

Un Makefile est obligatoire et doit compiler vos sources vers la sortie requise avec les drapeaux -Wall, -Wextra, et -Werror, en utilisant cc. Votre 

Makefile ne doit pas relier inutilement. 

Votre 

Makefile doit contenir au minimum les règles $(NAME), all, clean, fclean, et re. 

Il est recommandé de créer des programmes de test pour votre projet, bien que ce travail ne soit pas soumis ni noté. Cela vous permettra de tester facilement votre travail et celui de vos pairs. 

Soumettez votre travail sur votre dépôt Git assigné. Seul le travail sur le dépôt Git sera évalué. 

Partie Bonus (Optionnelle) ✨

Les bonus ne seront évalués que si la partie obligatoire est 

PARFAITE (complète et sans aucun dysfonctionnement). 

Vous pouvez obtenir des points supplémentaires en implémentant des fonctions additionnelles spécifiques aux bonus. Ces bonus doivent être dans des fichiers séparés (

_bonus.c/.h), sauf indication contraire. 

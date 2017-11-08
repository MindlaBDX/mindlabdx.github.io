---
layout: page
title: Les projets du hackathon
permalink: /projet_hackathon/
---

## En bref
* [Naming Game](###Le Naming Game: créons un langage en commun) 



###Projet 1 - Le Naming Game: créons un langage en commun

*Projet présenté par :* William Schueller - william.schueller at gmail.com
*Mots-clés décrivant le projet :* émergence du langage, curiosité, exploration conceptuelle, apprentissage actif
*Domaine(s) concerné(s) :* Intelligence artificielle, Modélisation des systèmes complexes, linguistique computationnelle, Semiotique experimentale,

Comment choisit-on les mots pour de nouveaux concepts? Et surtout, comment se met-on d'accord à l'échelle du groupe? Ce phénomène a lieu presque tous les jours sans que nous nous en rendions compte, de manière décentralisée.
Le Naming Game est un modèle computationnel de cette dynamique, faisant appel à des mécanismes assez simples mais permettant de recréer certaines dynamiques à des échelles diverses: dans un petit réseau social, comment se forment des groupes en désaccord, ou à l'échelle d un pays, quelles sont les régions susceptibles de développer une langue créole, ou quel est le nombre moyen de noms de couleurs différents dans une langue. Des simulations avec des 'agents fictifs' ou des robots permettent de comparer les résultats du modèle aux observations réelles.

Cependant, on ne sait pas si les stratégies individuelles mises en oeuvre dans ce type de modèle sont proches du comportement humain individuel ou non. Comment choisit-on ce dont on parle? Comment choisit-on de ne privilégier qu'un seul mot parmi plusieurs synonymes? Et quand choisit-on d'inventer de nouveaux mots?

De précédentes expériences de sémiotique expérimentale -- faisant interagir plusieurs personnes par ordinateur interposé -- commencent à répondre à cette problématique, mais ont fait apparaître une difficulté particulière:
Comment effectuer une expérience à grande échelle avec interactions réitérées entre des utilisateurs humains, sans que l'absence prolongée ou l'abandon individuel n'influent sur les autres utilisateurs?

Ce projet a plusieurs axes:
- implémenter sous forme d'application web/mobile une solution à cette problématique, en passant par des agents simulés 'partagés' entre utilisateurs. 
- implémenter la possibilité d'explorer toujours plus d'objets/concepts sur lesquels se mettre d'accord, et possibilité d'inventer des mots ou symboles de manière combinatoire.
- rendre l'implémentation attractive et ludique. Design graphique, mais aussi possibilité de transférer le feedback et l'interaction à une petite figurine imprimée en 3D, dont le visage est animé.

Une implémentation du jeu sous forme d'application web existe déjà (pour un utilisateur unique), et l'idée est de l'utiliser pour ne pas repartir de zéro.
sources: http://github.com/wschuell/ng_userxp 
et en fonctionnement: http://naming-game.bordeaux.inria.fr


###Projet 2 - DIY : Induction de rêves Lucides par flash lumineux

*Projet présenté par :*  Emma CHABANI -  emma.chabani at gmail.com
*Mots-clés décrivant le projet :* Rêve Lucide, Casque d'induction de rêve lucide, Conscience, Sommeil, EEG
*Domaine(s) concerné(s) :* Neurosciences, Sciences Cognitives, Imagerie mentale, Ingénieurie


Création d’un casque comme le dream light de Stephen Laberge et mesure de l’impact des flash lumineux sur le sommeil en phase de REM.
Le but consisterait dans un premier temps à recréer avec une Arduino, un casque permettant d’envoyer au dormeur des flash lumineux à des fréquences répétées pour essayer de lui induire un rêve lucide. Le dormeur sera au courant que pendant ses rêves il pourrait constater des flash lumineux. Ses flash lumineux serait sensé aider le rêveur à prendre conscience qu’il rêve.
De plus essayer de comprendre comment sont intégrés les signaux des flashs pendant différentes phases du sommeil (très peu de chance qu'on voit quelque chose en EEG dans ces conditions) mais pourquoi pas à l'échelle du rêve ou de l'induction d'hallucinations hypnagogiques liées aux flashs)
Cependant quel est l’impact de ses flash sur un dormeur en phase de REM.
Ce projet aura donc pour but de :
- Demander à un groupe de 5 personnes de réaliser un prototype reproduisant le comportement du Dream Light de Laberge.
- Enregistrer le signal EEG d’une personne en train de rêver sans Dream Light et avec Dream Light.
- Analyser les résultats et les confronter à la littérature.
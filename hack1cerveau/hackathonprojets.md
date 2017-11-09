---
layout: page
title: Les projets du hackathon
permalink: /projet_hackathon/
---
[//]: # (/hack1cerveau/projet_hackathon/)

<img src="/images/bandeau_hack1cerveau_avec_dates-lieu_sans_autres_logos.png" width="828">
<img src="/images/CC0_creative_common_from_pixabay/brain-2676370_960_720.jpg" width="350">
<img src="/images/CC0_creative_common_from_pixabay/artificial-intelligence-2228610_1920.jpg" width="375">

## En bref
* [Naming Game](#projet1)
* [Induction de rêves Lucides par flash lumineux](#projet2)
* [MoreWrong](#projet3)
* [Conquérir par le langage : biais cognitif, discours, et persuasion.](#projet4)
* [Vulgarisation du machine learning par réseaux de neuronnes avec des interfaces tangibles](#projet5)
* [IA Tetris/Snake pour Arbalet 127](#projet6)
* [Arts & Sciences 4 your Brain](#projet7)

## <a name="projet1"></a> Projet 1 - Le Naming Game: créons un langage en commun

**Projet présenté par :** William Schueller - william.schueller at gmail.com

**Mots-clés décrivant le projet :** émergence du langage, curiosité, exploration conceptuelle, apprentissage actif

**Domaine(s) concerné(s) :** Intelligence artificielle, Modélisation des systèmes complexes, linguistique computationnelle, Semiotique experimentale,

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


## <a name="projet2"></a> Projet 2 - DIY : Induction de rêves Lucides par flash lumineux

**Projet présenté par :**  Emma CHABANI -  emma.chabani at gmail.com , Philippe Giraudeau (philippe at giraudeau.eu)

**Mots-clés décrivant le projet :** Rêve Lucide, Casque d'induction de rêve lucide, Conscience, Sommeil, EEG

**Domaine(s) concerné(s) :** Neurosciences, Sciences Cognitives, Imagerie mentale, Ingénieurie


Création d’un casque comme le dream light de Stephen Laberge et mesure de l’impact des flashs lumineux sur le sommeil en phase de REM.
Le but consisterait dans un premier temps à recréer avec une Arduino, un casque permettant d’envoyer au dormeur des flashs lumineux à des fréquences répétées pour essayer de lui induire un rêve lucide. Le dormeur sera au courant que pendant ses rêves il pourrait constater des flashs lumineux. Ces flashs lumineux seraient censés aider le rêveur à prendre conscience qu’il rêve.
De plus, essayer de comprendre comment sont intégrés les signaux des flashs pendant différentes phases du sommeil (très peu de chance qu'on voit quelque chose en EEG dans ces conditions) mais pourquoi pas à l'échelle du rêve ou de l'induction d'hallucinations hypnagogiques liées aux flashs)
Cependant quel est l’impact de ses flashs sur un dormeur en phase de REM.
Ce projet aura donc pour but de :
- Demander à un groupe de 5 personnes de réaliser un prototype reproduisant le comportement du Dream Light de Laberge.
- Enregistrer le signal EEG d’une personne en train de rêver sans Dream Light et avec Dream Light.
- Analyser les résultats et les confronter à la littérature.

## <a name="projet3"></a> Projet 3 - MoreWrong

**Projet présenté par :** Basile Garcia - (basilegarcia at gmail.com) , Aurélien Nioche - ( nioche.aurelien at gmail.com)

**Mots-clés décrivant le projet :** modélisation ; prise de décision ; rationalité ; théorie des jeux ; behavioral game theory ; tablettes ; économie expérimentale

**Domaine(s) concerné(s) :** Théorie des jeux ; Économie comportementale et expérimentale

La théorie des jeux s'attache à décrire les interactions entre individus évoluant dans le cadre d'un jeu.
Afin de maximiser leurs gains potentiels, ces derniers sont amenés à établir des stratégies. La rationalité présumée des joueurs
est garante de l'optimalité de leurs décisions.
Ce type de joueur rationnel est couramment désigné sous l'expression d'Homo œconomicus.

Or, lorsque des humains prennent part à ces jeux, il est fréquent d'observer des divergences
entre les résultats obtenus et les issues prédites par la théorie.

Les participants à ce projet devront répliquer les résultats de sujets humains intervenant dans un jeu de type "ultimatum", en testant l'hypothèse selon laquelle les groupes font des choix davantage rationnels que l'individu dans les situations occasionnées par ce jeu (cf article en lien).

Afin de réaliser l'expérimentation, il sera nécessaire de programmer un jeu multijoueur sur la base d'une architecture client/serveur. Les joueurs constitueront les clients et seront munis de tablettes, tandis que le serveur (un PC) s'occupera de gérer les flux d'informations entre les différents périphériques.
Des notions de réseau seront donc requises, ainsi que de programmation : Java/Unity pour les tablettes + un quelconque langage disposant d'une libraire permettant l'envoi et la réception de requêtes sur un réseau local (python par exemple).
Enfin il faudra être capable de monter un protocole expérimental.

Une aide pourra être apportée à l'ensemble des tâches intervenant dans la réalisation du projet.

lecture complémentaires : https://en.wikipedia.org/wiki/Ultimatum_game ; http://sci-hub.io/10.1023/A:1009914001822


## <a name="projet4"></a> Projet 4 - Conquérir par le langage : biais cognitif, discours, et persuasion.

**Projet présenté par :** de Checchi Kévin - dechecchi.kevin@live.fr

**Mots-clés décrivant le projet :** biais cognitif - discours - persuasion

**Domaine(s) concerné(s) :** sciences cognitives, sciences du langage, sciences de l'éducation, sciences politiques

Les Sciences Cognitives ont permis d’approfondir très largement la compréhension des capacités mentales chez l’Homme telles que la perception, la mémoire, l’attention, ou encore la prise de décision. Les retombées de ces connaissances s’appliquent elles-mêmes dans des champs très variées (médical, éducation, marketing, économique, politique, etc) qui impactent la vie quotidienne de tous. L’une des facettes de la cognition humaine qui a le plus suscité d’intérêt concerne les limites des fonctions mentales et les biais liés à leur fonctionnement. L’exemple le plus parlant pour illustrer ce phénomène concerne la publicité mettant à profit divers phénomènes cognitifs - congruence cognitive, conditionnement associatif, activité de stéréotype, etc - pour optimiser la vente d’un produit. Une application moins connue et pourtant tout aussi lourde de conséquence est l’optimisation des discours à l’aune des biais cognitifs. Que cela concerne la vie politique, notre vie professionnelle ou personnelle, l’utilisation de ces biais cognitifs sert à améliorer la dimension persuasive d’un discours. Dans une société où la parole est utilisée comme moyen de pouvoir, il est fondamental que tout à chacun soit conscient des stratagèmes pouvant être à l’œuvre afin de les convaincre d’une opinion. Il s’agit donc ici d’étudier comment les sciences cognitives nous renseignent sur les discours qui « hack » notre cerveau.
Ce projet visera à produire un contenu éducatif présentant les différents biais cognitifs permettant d’orienter la construction d’un discours pour optimiser sa fonction persuasive.
Plus particulièrement, le projet propose de s’organiser autour de plusieurs étapes:
- Une phase visant, grâce à la littérature, à chercher, définir, trier et sélectionner les biais cognitifs pertinents pour la thématique
- Une mise en lien entre les différents biais sélectionnés et la façon dont ils peuvent orienter la construction d’un discours en spécifiant le contexte
- La construction d’un discours persuasif réinvestissant au maximum les biais cognitifs sélectionnés. Il est conseillé de se pencher sur un discours traitant d’un sujet non consensuel et abordant un point de vue non majoritaire. Il peut reprendre un discours déjà existant et étant considéré par l’opinion public comme non persuasive.
- Le discours pourra être filmé. Un travail de montage vidéo permettra de faire apparaitre les différents biais cognitifs au moment de leur intervention dans le discours. Enfin, il peut être intéressant de mettre en comparaison le discours d’origine et celui produit par l’équipe de travail.

## <a name="projet5"></a> Projet 5 - Vulgarisation du machine learning par réseaux de neuronnes avec des interfaces tangibles.


**Projet présenté par :** Jérémy Laviole - (laviole at rea.lity.tech) , Philippe Giraudeau (philippe at giraudeau.eu)

**Mots-clés décrivant le projet :** Réalité augmentée, interface tangible, processing, réseaux de neuronnes, vision par ordinateur

**Domaine(s) concerné(s) :** Vulgarisation sur machine learning

L'objectif du projet est d'aboutir à un réseau de neurones capable de distinguer des classes d'images.
Ce projet suis un principe de design appelé «tangible bits». C'est à dire que l'essentiel des éléments du système est incarné dans des objets. Ainsi nous proposons de créer lors du Hackathon:
- Des classes d'images comme base de l'apprentissage. Ces images seront dessinées physiquement sur les petites cartes.
- Des réseaux de neurones où chaque neurone est incarné par un petit objet coloré.

Ça serait très intéressant de partir d'une vidéo d'introduction ou d'exemples interactifs très simple pour créer des réseaux qui distinguent des formes très simples. Le but est trouver les limites de chaque réseau, et imaginer ce que pourrait être des réseaux complexes et puissants.

Les compétences idéales d'une équipe:
- Développement logiciel: Java / Processing / Ruby. (expertise Jérémy).
- Notions de base sur le perceptron multi-couche. (expertise Philippe).
- Expérience utilisateur, création d'interfaces, UX design.
- Design 2D + découpe Laser + peinture.
- Vulgarisation, scénarisation.


## <a name="projet6"></a> Projet 6 - IA Tetris/Snake pour Arbalet 127


**Projet présenté par :** Yoan Mollard - (yoan at arbalet-project.org) Baptiste Busch, Sébastien Forestier, Bhargav teja Nallapu

**Mots-clés décrivant le projet :**  machine learning, apprentissage, pixel art, tetris, retrogaming, arcade

**Domaine(s) concerné(s) :**  machine learning, reinforcement learning, apprentissage

Arbalet 127 est un mur pixelisé de 3m2 composé de 300 pixels colorés pilotables par ordinateur. Arbalet 127 est avant tout une oeuvre d'art, sur le thème du Pixel Art/Pop art, mais c'est également une oeuvre interactive qui permet de jouer à des jeux retro comme Tetris, Snake, Pong etc et qui est entièrement programmable en Python. Actuellement Arbalet 127 est en exposition au fablab de Cap Sciences, et les visiteurs peuvent se saisir de la manette pour jouer.

Ce projet consiste à créer une IA qui joue elle-même à Tetris ou Snake lorsqu'aucun visiteur n'a la manette entre les mains. La littérature foisonne de tentatives de créer des IA pour ces jeux cultes, reste à s'en inspirer pour les implémenter sur Arbalet 127, voire les améliorer. Les techniques de machine learning à utiliser ne sont pas définies à l'avance, un état de l'art des méthodes utilisées dans la littérature fera partie du hackathon. L'IA doit être implémentée en Python pour pouvoir utiliser le SDK d'Arbalet.

L'objectif à la fin du hackathon est de pouvoir visualiser sur Arbalet 127 des parties de Tetris jouées par l'ordinateur sans jamais perdre (partie infinie) et/ou un Snake qui parvient à remplir les 300 pixels sans se mordre la queue. Selon le nombre de participants l'équipe pourra soit choisir un des deux jeux, soit se scinder en deux sur Tetris et Snake pour creuser chaque jeu. Une IA triviale utilisant des champs de potentiel est déjà implémentée pour Snake mais elle perd très rapidement ; sur Tetris en revanche, toute l'IA est à faire.

**Lien vers une (ou plusieurs) page web :** [https://github.com/fablab127/arbasdk/wiki](https://github.com/fablab127/arbasdk/wiki)

## <a name="projet7"></a> Projet 7 - Arts & Sciences 4 your Brain (projet bonus)
**Projet présenté par :** Xavier Hinaut - (xavier.hinaut [at] inria [point] fr)

**Mots-clés décrivant le projet :** art, fablab, découpeuse laser, découpeuse vinyle, imprimante 3D, IRM, images scientifiques

**Domaine(s) concerné(s) :** art, matériel fablab, graphisme, neurosciences,

L'idée est de profiter un maximum des ressources et machines du 127° (le fablab de Cap Sciences) afin de créer des objets artistiques autour du cerveau ! Comme par exemple des lampes, supports, badges, logos, etc.

Juste un exemple parmi des millions sur ce qui pourra être fait : [une lampe en plexiglas](https://fablab.lacasemate.fr/?_escaped_fragment_=/projects/lampe-plexiglas-pilotable-en-wifi#!/projects/lampe-plexiglas-pilotable-en-wifi) avec une image d'image IRM\* gravée dessus. En mettant différentes "tranches" d'IRM et en mettant ces lampes les unes à côté des autres, on pourra donner l'impression d'avoir un cerveau complet illuminé !
\*IRM : Imagerie par Résonance Magnétique

<center><img src="https://fablab.lacasemate.fr/uploads/project_image/1598/project_image.jpg" width="300"><img src="https://fablab.lesusinesnouvelles.com//?_escaped_fragment_=/projects/light-fox-wood#!/projects/light-fox-wood" width="300"></center>


<BR>
Pour vous inspirer, voici des exemples par dizaines de projets du fablab : [examples projet 127°](https://www.fablab127.net/#!/projects?whole_network=t)

N'hésitez pas à me contacter si vous voulez discuter d'oeuvres à réaliser !

<BR><BR>
<center>[**--- Revenir à la page principale du hackaton ---**](/hack1cerveau/)</center>

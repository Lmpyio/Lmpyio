Robot Mobile - Contrôle de LED et Navigation

	1) Description

Ce projet consiste en la réalisation d’un robot mobile capable de se déplacer dans un environnement type labyrinthe. Il intègre plusieurs fonctionnalités de base, notamment le contrôle d’une LED et différents modes de déplacement, dont un mode suivant un mur automatiquement afin de sortir du labyrinthe.

Le robot peut :
- Allumer une LED ("x")
- Eteindre une LED ("p")
- Avancer en ligne droite ("z")
- Tourner à droite ou à gauche ("d" / "q", respectivement)
- S'arrêter ("s")
- Se déplacer de manière autonome ("e")
- Suivre un chemin prédéfini par l'utilisateur ("u")(puis chaque action est décrite)

Vous pouvez aussi quitter le programme à l'aide de la touche ("x")

Ce projet permet de découvrir les principes de la programmation sur système d'exploitation, ainsi qu'un début à la résolution d'un labyrinthe

---

	2) Fonctionnalités

-**Contrôle de LED** :  
  - La LED peut être allumée ou éteinte pour indiquer un état. Notre projet initiale étant de pouvoir dessiner à l'aide du robot, nous avons gardé l'allumage de la led, pouvant symboliser ici crayon posé et crayon levé.

-**Déplacements manuels** :
  - Avancer 
  - Tourner à droite
  - Tourner à gauche
  - Stopper le mouvement

-**Mode automatique** :
  - Le robot peut explorer de lui-même un labyrinthe ou un environnement prédéfini :
	- S'il y a un mur en face, il tourne à droite
	- S'il ne détecte plus de mur à gauche, il tourne à gauche, de sorte à suivre le mur gauche constamment
	- Sinon, il avance

-**Mode programmation** :
  - Créer un parcourt
  - Définir tout le parcours
  - Modifier une étape du parcours
  - Détruire le parcours
  - Afficher le parcours
  - Suivre le parcours
  - Sauvegarder un parcourt
  - Charger un parcours
  - Quitter le mode programmation 

---

	3) Fonctionnement

Afin de lancer le programme, il faut rentrer les commandes suivantes:

	cd DUVERGER_DESALLIERDUPIN/src

	make all

	../bin/go

# **Exercice 1 \- Prototype simple déployé**

[![Prototype réference](ex1-proto-ref.png)](https://max-lacasse-maisonneuve.github.io/2J2-Exercices/ex1/index.html)

## **Synopsis du jeu**

Une méga-cité industrielle automatisée s'est effondrée après une panne majeure de son noyau de contrôle. Les systèmes sont partiellement fonctionnels, mais de nombreux obstacles et dangers errent dans les rues.
Le joueur doit explorer différents secteurs de la cité, chacun correspondant à un niveau du jeu.

### **Chapitre 1 : Les quais d'amarrage**

Vous avez été appelé pour une mission de sauvetage dans la méga-cité. Votre objectif est d'atteindre une zone de sécurité en évitant les obstacles fixes et mobiles qui se trouvent sur votre chemin.

## **Objectif de l'exercice**

Vous devez créer un prototype d'un jeu où le vaisseau contrôlé par la joueuse peut s'évader des obstacles fixes et mobiles avec l'objectif d’arriver à une zone de finale. L'équipe qui s'occupe des médias n'est pas encore prête donc vous utiliserez des formes géométriques simples pour représenter les différents éléments du jeu (greyboxing).

Voici [le lien pour un exemple jouable](https://max-lacasse-maisonneuve.github.io/2J2-Exercices/ex1/index.html).

## **Exigences requises**

- L'avatar (un triangle ou «vaisseau») commence à une zone de départ sur la gauche. Il utilise le script fourni pour la logique de détection d'entrée et le déplacement.
- Quelques obstacles fixes (les carrés ou «planètes») sont placés au niveau.
    - Ils doivent utiliser le script fourni pour la détection de collisions.
- Quelques obstacles mobiles (les hexagones ou «météores») sont placés au début du jeu de façon aléatoire.
    - Ils commencent toujours hors l’écran dans une rangée prédéterminée de l'espace du jeu.
    - Ils ne doivent jamais bloquer les zones de départ et de finale.
    - Ils doivent utiliser le script fourni pour la détection de collisions.
    - Ils doivent se déplacer et croiser l'écran avec une vitesse aléatoire configurable à l’Inspector.
    - Quand ils sortent de l’écran, ils sont téléportés au côté opposé de l’écran (mécanique de _warp_).
- L'arrière-plan a une couleur personnalisée et différente du défaut d'Unity.
- La caméra MainCamera doit avoir un Size de 10\.
- L’aspect de la fenêtre `Game` doit être `16:9 Aspect`.
- Le code du projet doit être hébergé sur un dépôt GitHub.
    - Le dépôt doit être créé dans l’ organisation du cours (**26h-2j2**).
    - Le dépôt doit être nommé **NomPrenom-Ex1**. _Ex. RossBob-Ex1._
- Les messages de commits sont descriptifs des changements réalisés.
- Une version compilée (un _build_) doit être déployée sur GitHub Pages dans le dossier `docs` du dépôt.
    - Le _build_ doit être fonctionnel et stable.

## **Remise**

- Date : Fin de la semaine 3 (cours 6).
- Vous devez remettre sur Teams:
    - une archive UnityPackage de votre projet.
    - un lien pour le dépôt GitHub du projet.
        - Format : _Ex. https://github.com/26h-2j2/NomPrenom-Ex1._

## **Critères**

- Fonctionnement correct du produit multimédia réalisé
    - Les fonctionnalités demandées sont présentes et cohérentes.
    - Le niveau a une bonne ergonomie et est jouable.
    - Le dépôt GitHub est dans l’organisation du cours, accessible et bien nommé.
    - Les messages de commit sont descriptifs des changements réalisés.
    - La version compilée (_build_) est fonctionnelle et stable sur GitHub Pages.
- Contrôle fonctionnel des médias et de leur affichage
    - La présentation visuelle respecte le concept de _greyboxing_.
- Utilisation adéquate des éléments du langage
    - La variabilité aléatoire est utilisée efficacement lors de la configuration des obstacles mobiles.
    - La vitesse des obstacles mobiles est configurable à l’`Inspector`.
    - Les objets mobiles se déplacent et respectent la mécanique de téléportation (_warp_).
- Élaboration judicieuse des algorithmes et du code
    - Le projet exploite efficacement les concepts d'algorithmique vus en classe (variable, conditions et fonctions).
    - Le code est bien structuré et commenté.
    - Les variables et fonctions respectent les conventions de nommage vues en classe.
    - Les scripts fournis sont utilisés adéquatement.
    - Le code ne contient pas de bug évident ou de code mort (code inutile en commentaire).

## Notes

Ce travail est individuel. Toute forme de plagiat entrainera la note de 0 conformément aux politiques académiques de l'institution. L'utilisation de l'intelligence artificielle pour générer du code n'est pas permise et sera considérée comme du plagiat.

Si vous utilisez du code qui n'est vu en classe, vous devez noter en commentaire chaque ligne en expliquant pourquoi cette ligne est plus utile et ce qu'elle remplace.

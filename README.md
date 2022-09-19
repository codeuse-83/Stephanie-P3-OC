# Dynamisez une page web avec des animations CSS 

*Compétences évaluées* 

* Mettre en œuvre des effets CSS graphiques avancés
* Assurer la cohérence graphique d'un site web
* Mettre en place une structure de navigation pour un site web
--------------------------------------------------------------
*Fonctionnalités*

*Page d'accueil*

Affichage de la localisation des restaurants. À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu.
Une courte présentation de l’entreprise.
Une section contenant les 4 menus sous forme cartes.  Au clic sur la carte, l’utilisateur est redirigé vers la page du menu.
---------------------------------------------------------------------------------------------------------------------------------------------------------
*Pages de menu*

4 pages contenant chacune le menu d’un restaurant.
Footer:

Le footer est identique sur toutes les pages.
Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.
Header:

Le header est présent sur toutes les pages.
Sur la page d’accueil, il contient le logo du site.
Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil.
Effet graphique et animations:
---------------------------------------------------------------------------------------
*Boutons*

Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir.  L’ombre portée devra également être plus visible.
Un bouton "J’aime" en forme de cœur est présent sur la maquette.  Au clic, il devra se remplir progressivement. Pour cette version, l’effet peut apparaître au survol sur desktop au lieu du clic.
Page d’accueil:

Un __“loading spinner”__ devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS. Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.
Pages de menu:  

À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.
Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension. Un exemple de l’effet attendu est fourni.
Contraintes techniques:  

le site sera développé en utilisant l’approche __mobile-first et seules des maquettes mobiles seront réalisées.__
Sur tablette et desktop, le site devra s’adapter, leur mise en page est libre.
Le développement devra se faire en __CSS (pas de librairie),_ sans JavaScript.__
Aucun framework ne devra être utilisé, en revanche l’utilisation de SASS serait un plus.
Aucun code CSS ne devra être appliqué via un attribut style dans une balise HTML.
Les couleurs de la charte sont, en couleur primaire le #9356DC, en couleur secondaire le #FF79DA, et en couleur tertiaire le #99E2D0.
La police du site est, Logo et titres Shrikhand, et Texte: Roboto.
Contraintes d'exercices:

L’ensemble du site devra être responsive sur mobile, tablette et desktop.
Les pages devront passer la validation __W3C en HTML et CSS sans erreur.__
Le site doit être parfaitement compatible avec les dernières versions desktop de Chrome et Firefox.
Un lien vers votre repository GitHub.
Un lien vers la page web du site.
L'intégration d'images issues des maquettes ne sera pas acceptée : vous devez recréer les éléments de zéro (titres, texte...).  
------------------------------------------------------------------------------------------------------------------------------
*Technologies*  

__HTML__

__CSS__  

__SASS__  

__Font Awesome ( importation d'icones )__  

__Google Font: Logo et titres Shrikhand, Texte: Roboto ( importation des links )__

Contribution au projet

Cet excercice est opensource et, est mon projet 3 dans le cadre de la formation 'Developpeur web' Openclassrooms.
-----------------------------------------------------------------------------------------------------------------
*Auteur*
code: Stéphanie

*Licenses*
__Font Awesome ( utilisation d'icones gratuits )__

__GitHub ( stockage gratuit des fichiers et déployement gratuit sur GitHub pages )__

__Google Font ( utilisation de police d'écriture gratuite )__

__SASS ( utilisation de préprocesseur gratuite )__

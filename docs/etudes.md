---
layout: default
nav_order: 4
title: Études et choix techniques
---

# Études et choix techniques

# Mécanisme partie microcontrôleur:
Le mécanisme du Drawbot repose sur un processus assez simple mais bien établi,
similaires à des principes utilisés dans les imprimantes 3D. Pour mieux comprendre
son fonctionnement, voyons les différentes étapes du processus :


# 1 - Conversion d'image JPEG en SVG :
Le processus débute par l'envoi d'une image sous format JPEG. Cette image
est ensuite convertie en un fichier SVG (Scalable Vector Graphics) pour la
vectoriser.

Contrairement aux images JPEG qui sont basées sur des pixels qui sont
fusionnés en une seule image, les fichiers SVG sont basés sur des vecteurs et
conservent les informations sur chaque élément graphique séparément, tels
que les lignes, les courbes, les formes, etc.

Ainsi, en convertissant l'image en SVG, le DrawBot peut suivre précisément
les contours et les formes lors du dessin et le reproduire encore une fois
précisément sur le tableau.


# 2 - Analyse du SVG :
Une fois convertie en SVG, l'image est analysée pour extraire les coordonnées
x,y des trajectoires de dessin. Elles représentent les contours des formes et
des lignes dans l'image, et serviront à guider le DrawBot lors du dessin.


# 3 - Transmission des coordonnées au microcontrôleur :
Les coordonnées extraites sont ensuite transmises au microcontrôleur qui
traitera les instructions reçues et de contrôlera les moteurs et le servomoteur
pour effectuer le dessin.


# 4 - Génération des instructions de mouvement :
En fonction des coordonnées reçues, le microcontrôleur génère une séquence
d'instructions de mouvement. Ces instructions déterminent précisément où le
DrawBot doit se déplacer sur le mur et à quelle vitesse, ainsi que quand il doit
lever ou abaisser le stylo pour dessiner.


# 5 – Le dessin :
En suivant les instructions générées, le DrawBot effectue les mouvements
nécessaires pour reproduire le dessin sur le mur. Cela implique le
déplacement précis du DrawBot sur toute la surface du tableau mural, ainsi
que le contrôle du mécanisme de levage du stylo pour le positionner
correctement en fonction des besoins du dessin.


# Utilisation du G-Code - Pour les imprimantes 3D :
Le langage de programmation utilisé pour contrôler le mouvement des
imprimantes 3D est souvent le G-Code. Un langage de programmation à
contrôle numérique composé d'une série de commandes appelées G-Code.
La plupart de ces commandes commencent par un G (d'où le nom G-code).

# Logiciel et firmware pour envoyer le svg et piloter le robot :

Voici un schéma pour expliquer simplement comment cela fonctionne :


# Etude du robot partie dessin:

Gcode dans la sd – plus tard par wifi …
Moteur tourne pour faire bouger le robot
Servo sactive pour avancer ou reculer le stylo – écrire ou non


# Etude branchement et technique – carte kicad
Regulateur +image
Driver ou les pates sont connectées et pk + pk condo
Servo IDEM
Screen schema et footprints de kicad…





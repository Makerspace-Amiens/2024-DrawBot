## **Objectifs du Projet**

Les objectifs de notre projet sont définis en trois parties différentes, chacune contribuant à la réalisation réussie du Drawbot ainsi qu'à notre développement personnel en tant qu'ingénieurs.

### **Objectifs du robot :**

1. **Concevoir un Drawbot fonctionnel et précis :**  
   Notre priorité est de créer un Drawbot capable de dessiner sur un tableau blanc de manière plus ou moins précise. Cela implique la mise en place d'un mécanisme fluide pour le robot contrôlé par deux moteurs que nous devrons choisir précisément.

2. **Utilisation de technologies durables et bien adaptées :**  
   Le but, comme nous venons de le mentionner ci-dessus, est d’intégrer des technologies de contrôle de mouvement pour que le robot dessine précisément. Les technologies devront aussi être durables, afin d’assurer la robustesse et la fiabilité du Drawbot. Cela permettrait à de futurs ingénieurs de retravailler avec ce projet.

3. **Optimiser les algorithmes :**  
   Afin de rendre tous les codes utilisables pour une évolution future du projet, l’objectif sera de bien commenter chaque partie de notre code. Il sera aussi préférable d’optimiser au maximum les algorithmes pour rendre le robot plus rapide.

4. **Fournir une documentation complète :**  
   Comme il est pas mal mentionné, le but est que le projet soit repris. Pour faciliter la tâche aux prochains, nous documenterons au maximum chaque étape du projet.

### **Objectifs d’améliorations – Si le temps le permet :**

5. **Intégration d'un contrôle à distance :**  
   Nous pourrions étendre les capacités du Drawbot en le connectant à un serveur, permettant ainsi un contrôle à distance. Cela serait utile pour le superviser ou ajuster le processus de dessin à distance (pour le mettre en veille, vérifier les bugs, etc.)

6. **Développement de notre propre interface utilisateur :**  
   Nous pourrions aussi créer une interface utilisateur simple et accessible, où l’on pourrait charger les images à dessiner, sélectionner des options de dessin et contrôler le Drawbot à distance.

### **Les objectifs personnels :**

1. **Évaluer et développer nos compétences techniques :**  
   Acquérir et approfondir nos connaissances en programmation, électronique et même en mécanique.

2. **Développer nos compétences en travail d’équipe, en gestion de projet et en résolution de problèmes :**  
   Améliorer notre capacité à planifier, gérer nos ressources et communiquer ainsi qu'à respecter un cahier des charges.

## **Existant**

Plusieurs versions de ce projet ont déjà été développées, cette immense source d'informations nous permettant d'imager notre projet et d'en tirer les meilleurs éléments. Notre version de ce projet vise à innover dans l'efficacité et l'accessibilité, notamment grâce à notre carte ESP32 permettant d'être utilisé via wifi/bluetooth.

Le Drawbot utilise le même système que les fraiseuses ou les imprimantes 3D (avec un axe en plus). Pour comprendre ce système, je vous renvoie à la partie étude technique.

Notre projet n’est pas une innovation, beaucoup d’autres Drawbot ont déjà été conçus avant le nôtre. Il y aura à la fin de cette section tous les liens des autres Drawbot dont nous avons pu nous inspirer.

### **Logiciel et firmware déjà existant pour envoyer le SVG et piloter le robot :**

En cas de manque de temps, de problèmes techniques ou juste comme inspiration, il existe déjà un firmware ainsi qu’un logiciel permettant de piloter un Drawbot Arduino tout en suivant le même principe utilisé par les imprimantes 3D :

https://data.emotion-tech.com/ftp/Datasheets_et_sources/Lab_et_news/Scriboo/eMt_Scriboo_release_1.1.zip

D’autres Drawbot :

- https://www.mydiy.dev/realisations_drawbot.html
- https://blog.zenika.com/2021/10/21/drawbot-le-robot-dessinateur-du-devfest-🖊/
- https://www.reprap-france.com/article/realisez-vous-meme-un-drawbot-scriboo

## **Cahier des Charges**

Le Drawbot doit respecter certaines spécifications techniques et fonctionnelles :

1. **Précision du dessin :** Le dessin doit être reproduit à l'identique.
2. **Dimension du support :** Adaptable à différents supports muraux.
3. **Interface utilisateur :** Interface simple pour le

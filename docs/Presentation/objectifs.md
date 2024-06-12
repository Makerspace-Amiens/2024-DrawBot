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

# D’autres Drawbot :

https://www.mydiy.dev/realisations_drawbot.html

![exemple1](../images/exemple1.png) 

https://www.reprap-france.com/article/realisez-vous-meme-un-drawbot-scriboo

![exemple2](../images/exemple2.png) 

# A plus grande échelle :

**Botsy**, le robot de dessin mural qui permet de réaliser des dessins sur des surfaces verticales telles que des murs. 
Ce robot est très apprécié des artistes et des designers pour sa capacité à transférer et à agrandir des motifs complexes avec précision. 
Il est utilisé pour créer des fresques murales, des décorations intérieures et des projets artistiques sur divers matériaux, comme le verre, le bois, et le métal. Botsy se distingue par sa portabilité et sa facilité d'utilisation, ce qui en fait un outil précieux pour les professionnels cherchant à automatiser et à accélérer le processus de dessin 

https://www.botsy.com/
![Botsy](../images/botsy.png) 

**Plotly, à handwriter robot**

Ce drawbot est conçu pour réaliser des dessins et des tracés complexes avec une grande précision. Utilisé principalement avec des Raspberry Pi, PlottyBot est capable de dessiner des illustrations détaillées sur des surfaces plus grandes, transformant des images numériques en art physique. Ce projet est particulièrement apprécié pour sa flexibilité et sa capacité à traiter des projets artistiques variés, allant des simples croquis aux œuvres complexes​

https://hackaday.com/2022/02/07/plottybot-a-drawbot-that-plots-a-lot/
![mit](../images/plotly.png) 

## Actualité

Le 26 mai 2024, sur TF1 pour le 20h une émission est passée au sujet de l'impression 3d et du milieu de l'art, on à pu y voir une multitude de peinture recrées grâce à l'IA.

L'élément phare était un autoportrait de Van Gogh.

![vangogh](../images/20h.png)

C'est une œuvre complétement générée par l'IA, et réalisée par une imprimante 3D : un autoportrait très réaliste, dont l'artiste avait recouvert l'ébauche, faute de moyens pour acheter des toiles.

Citation de l'article :
"Face à une toile supposée de Van Gogh, une visiteuse reste perplexe. "Je me suis dit, c'est le style de Van Gogh, mais je sais que ce n'est pas une de ses toiles parce que je connais un petit peu le peintre, donc, ça m'a intrigué", explique Agathe au micro de TF1. Bien vu de sa part, car l'artiste de ce tableau n'est autre qu'une intelligence artificielle, aidée d'une imprimante 3D"

https://www.tf1info.fr/high-tech/video-reportage-nouvelles-technologies-quand-l-ia-intelligence-artificielle-termine-des-oeuvres-inachevees-de-van-gogh-2300987.html

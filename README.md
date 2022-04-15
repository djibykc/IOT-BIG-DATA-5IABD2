# IOT-BIG-DATA-IABD2
For school project


# `Ma maison connectée` : Équipement d'objet connectés


## Equipe 
- Djiby  CASSE
- Mounir AMIA
- Ismail MANÉ
- Alpha SOW

## Présentation : MMC

Ma maison connectée est un projet IoT qui permet à ses utilisateurs de disposer d'un espace de vie idéal et confortable.



## fonctionnalités
Les capteurs connectés à la carte microcontrôleur sont les capteurs de détecteur de fumée, PIR, Ultrasonic et LDR.
- Le détecteur de fumée est utilisé pour détecter le gaz en cas de fuite.
- Les données détectées par les capteurs sont alors en cas de fuite de gaz, le circuit d'alarme est actif.
- Les ultrasons sont utilisés pour l'ouverture automatique de la porte d'entrée si quelqu'un se trouve devant la porte.
- Le PIR est utilisé pour la détection des humains et allume le ventilateur. De plus, le ventilateur est contrôlé manuellement.
- LDR est utilisé pour le contrôle automatique de la lumière à la maison si quelqu'un est à la maison la nuit, l'ampoule est automatiquement allumée et à l'heure dey elle s'éteint automatiquement.

Le capteur de gaz détectera le niveau de fuite de gaz et affichera un message en fonction de celui à afficher, par ex. Low, Med, High et si l'intensité est très élevée, le message Exit s'affiche. Le LDR / PHOTORESISTOR fonctionne sur l'intensité de la lumière la nuit, l'ampoule est automatiquement allumée et le jour, l'ampoule est éteinte. Et l'essentiel est que le circuit du ventilateur et de la lumière ne soit actif que lorsque quelqu'un se trouve à l'intérieur de la pièce ou devant le capteur PIR.


## 3D modeling
### C'est quoi une maison connéctée

![alt text](https://github.com/djibykc/IOT-BIG-DATA-5IABD2/blob/main/images/C-est-quoi-une-maison-connectee.jpeg?raw=true "C-est-quoi-une-maison-connectee")


- Lien : https://www.tinkercad.com/things/
- Rendu : 

![alt text](https://github.com/djibykc/IOT-BIG-DATA-5IABD2/tree/main/images/model3D01.png?raw=true "3D modeling")

![alt text](https://github.com/djibykc/IOT-BIG-DATA-5IABD2/tree/main/images/model3D02.png?raw=true "3D modeling")

## TinkerCad
- Lien : https://www.tinkercad.com/things/hmXcXTGqKur-ma-maison-connectee/editel?sharecode=q673tlGWTQjFFjTj_9Vh7nI094h60LqgwqZvvPU5tNw
- Rendu : 

![alt text](https://github.com/djibykc/IOT-BIG-DATA-5IABD2/blob/main/images/tinkercadMMC.png?raw=true "TinkerCad")


## Pièces

- Arduino
- DÉTÉCTEUR DE FUMÉE
- PIR
- LDR
- Dc power source (Any 12v)
- Écran LCD 16*2 
- Source d'alimentation CC (Tout 12v)
- Carte relais de 2 canaux

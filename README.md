> 🎥: Youtube | 🐙: GitHub  | 💾: Commit de solution  | 📝: Faites-le vous-même | 📕: Manuel    

**Apprendre à créer un Micro:Bit puis l'utiliser avec Godot XR Tools**

* Avant l'atelier :
  * Faire le tutoriel de Brackeys sur la 2D [🎥](https://www.youtube.com/watch?v=LOhfqjmasi0)  
  * Pratiquer un peu Git et GitHub pour connaître les bases. [🐙](https://github.com/EloiStree/HelloGit/issues)
  * Jetez un coup d'oeil à la doc de GDScript [📕👁️](https://docs.godotengine.org/en/stable/tutorials/scripting/gdscript/gdscript_basics.html)
  * Un jeu, c'est des cubes et des ronds... C'est quoi un cube ? [🎥🐷](https://youtu.be/fT_yVg7_ECg?t=6) 
* Allons faire un simple cube pour le fun d’apprendre Godot [🎥](https://www.youtube.com/watch?v=tbfzr3zpOBc)  
* **Créer** une LED avec un script pour changer la couleur [💾](https://github.com/EloiStree/2026_03_20_godot_hello_micro_bit#103e56528e9f722b197b621eaf7b78569963ac0e) [🎥](https://www.youtube.com/watch?v=jsYthLYksqA&t=46s) [📝](https://github.com/EloiStree/2026_03_20_workshop_hello_micro_bit/blob/main/start_from/E0_LED.md)
* **Sauver le projet** avec Git [🎥](https://www.youtube.com/watch?v=OgYPy7lx0Ro)
* **Créer un tableau de LED 5x5** avec la scène de LED [💾](https://github.com/EloiStree/2026_03_20_godot_hello_micro_bit#c9bd120a0b8e7554180fdbd6058c06cf72b16a36) [🎥](https://youtu.be/Tq3iMY05yEE)
[📝](https://github.com/EloiStree/2026_03_20_workshop_hello_micro_bit/blob/main/start_from/E3_ARRAY.md)
* **.glb** pour notre Micro:Bit. 
* **Les Dictionaires** avec les "Micro:bit Image"
* **Array2D** Shift: Left, Down, Up , Right
* **Button A et B**
  * Un Script et une Scene [💾](https://github.com/EloiStree/2026_03_20_godot_hello_micro_bit.git#ae27e5571bee337a4c3ca35a6a6261cbdfa13937)
  * Area3D et input_event [💾](https://github.com/EloiStree/2026_03_20_godot_hello_micro_bit.git#b6d4fce5317db19a8029eb6a166a9a338dfede8e)
  * Area3D et entered exited [💾](https://github.com/EloiStree/2026_03_20_godot_hello_micro_bit.git#b6d4fce5317db19a8029eb6a166a9a338dfede8e)
  * Input Raw
  * Input Map
  * With Mouse for debug
  * Animation dans Godot
  * With Collision for future finger touch
* **Pins** Du Micro:Bit et class en Godot 
* Design pattern de Facade pour notre Micro:Bit ?
* Transformer un project Godot en addons git.

**Nouveau depart**:
> On a un Micro:bit avec un facade 🫡.   
-  Regardons ou on en est niveau de GDScrip [📕👁️](https://docs.godotengine.org/en/stable/tutorials/scripting/gdscript/gdscript_basics.html)
-  Regardons ou on en est en C# ou en Rust


Une fois le Micro:bit fait hors de la VR:
* Faire un Cube dans le casque [🎥](https://www.youtube.com/watch?v=yMFC_DTZ0fQ)
* C est quoi un casque VR ? [🎥](https://www.youtube.com/watch?v=tweBgb79VyE&t=292s)
* Allons plus loin dans ce qu'est la VR en general [🎥](https://github.com/EloiStree/HelloOneDayGodotXR/tree/main)
* Pratiquons Godot XR Tools [🎥](https://github.com/EloiStree/HelloGodotXR/issues/25)
  * Pick
  * Snap 

---------------


# Godot Package: Micro bit

> Workshop for Godot XR students: Try to recreate a Micro:bit API in XR  



Dans le cadre de l’apprentissage de la programmation avec Godot et du développement d’applications XR orientées industrie (hors jeu vidéo),   
je vous propose un exercice « simple » :    

Vous avez un GLB du micro:bit.    
Ajoutez, couche par couche, des fonctionnalités pour le simuler.    

C’est une demande typique sur le marché de la VR, example:

> Cet appareil à 10 000 $ dans un laboratoire prend 3 jours à utiliser et coûte 400 $ à chaque test.
> Sans compter le temps d’un senior qui doit former la nouvelle recrue.
> Permettre aux employés de s’entraîner sur la machine avant de l’utiliser réellement.
> (C’est aussi généralement accompagné de télémétrie pour observer l’apprenant.)   

Nous allons pratiquer sur un appareil très connu : le Micro:bit.
[<img width="628" height="271" alt="image" src="https://github.com/user-attachments/assets/e2037301-551d-49f7-ba7a-87f037affba0" /> ](https://python.microbit.org/v/3)

Download assets:
- [microbit_3d_and_svg.zip](https://github.com/user-attachments/files/26150152/microbit_3d_and_svg.zip)  


Éditeurs :
* [Python Editor](https://python.microbit.org/v/3)
* [Microsoft Block Editor](https://makecode.microbit.org)

Arrêtez-vous quand vous en avez marre,   
mais fixez-vous le challenge de publier l’application sur Itch.io   
dans une version portfolio finalisée avant la fin de l’atelier.    


Apprenez à travailler par couches de MVP.   
Votre application doit être jouable en APK à chaque fin d’atelier.    

C'est un exercice à faire seul   
pour les parties faciles du projet.   

Vous devrez vous mettre en groupe pour les parties plus compliquées :    
température, batterie, gyroscope, accéléromètre, sandbox…   

Sur ce, bonne chance. 🍀🫡
Et que le code soit avec vous 🧨


-------------

Si vous êtes en présentiel dans mon cours,
vous devez avoir, à la fin de l’atelier :

* Un projet Godot XR d’exemple sur GitHub (privé/public)
* Un projet Godot non-XR pour travailler sur l’addon sans casque (privé)
* Un addon micro:bit en submodule, utilisable par d’autres développeurs (non-XR) (public)
* Un addon d’exemple en submodule, référant votre addon et Godot XR Tools (public)
  * Une utilisation minimale de :
    * Pick up
    * Snap
    * Attraper à distance
* Un compte Itch.io avec une page pour votre portfolio de fin d’atelier


Ma solution se trouve dans la branche suivante :
[To Add]

Une branche vide avec le minimum nécessaire se trouve ici :
[To Add]

Vidéos step-by-step ici :
[https://www.youtube.com/@EloiTeaching/search?query=Micro](https://www.youtube.com/@EloiTeaching/search?query=Micro)




---

## Liste des features (du plus facile au plus difficile)

* Créer une scène pour une LED
* Créer un script qui permet de gérer la couleur et la transparence basée sur un float
* Créer une scène avec 25 scènes de LED
* Créer un script qui permet de gérer les 25 LEDs avec du code :
  * Une LED à la fois
  * Avec un tableau de floats
  * Avec un string
  * Avec un énumérateur de strings par défaut
* Créer une animation pour une scène de boutons (il y en a 3 sur le Micro:bit)
* Faire un script pour changer d’état avec les boutons
* Ajouter les trois boutons à votre scène globale du Micro:bit
* Il y a 3 boutons qui, une fois touchés, produisent un vrai ou un faux par capacité :
  * Logo
  * Pin 1 et 3
* Avec Godot XR Tools, vous pouvez snapper des objets :
  * Créer un adaptateur 3D qui peut recevoir un snap du Micro:bit
  * Il reçoit une référence vers la façade que vous avez créée
  * Cet adaptateur permet de s’ajouter sur le Micro:bit :
    * Lecture
    * Écriture
    * Pins rouge, noir, jaune :
      * Noir : ground
      * Rouge : haut potentiel
      * Jaune : signal
        * Un signal peut être entrant ou sortant en électronique
  * En MicroPython, par défaut, il n’y a que 3 pins analogiques, les autres sont digitales

## To do

* Accéléromètre
* Gyroscope
* Température du jeu
* Son du jeu
* Batteries
* Pins
* ~Bluetooth~
* RT XT
  * UDP
  * WebSocket
* GDScript Sandbox pour coder avec votre Micro:bit
   
---
   
## 3D

Vous avez à disposition deux modèles.

Celui-ci est gratuit mais approximatif :   
Il est en CC, je l’ai donc mis dans le projet en gardant la licence.   

[<img width="597" height="526" alt="image" src="https://github.com/user-attachments/assets/f49143e3-78e3-48b6-bae4-88fb7fd0e39c" />](https://sketchfab.com/3d-models/microbit-assemby-f0c6ec58eefc47afaab08d8de07e1158#download)     
[Cult3D](https://cults3d.com/en/3d-model/gadget/micro-bit-pequicraftminecraft) - [SketchFab](https://sketchfab.com/3d-models/microbit-assemby-f0c6ec58eefc47afaab08d8de07e1158#download)    

Et il y a une version payante faite à la sueur de son front par [@sitetechnofr](https://cults3d.com/en/users/sitetechnofr/3d-models) :      

[<img width="1272" height="623" alt="image" src="https://github.com/user-attachments/assets/77b3d3b4-f592-4fdf-9c48-8c1edbd8615e" />](https://sketchfab.com/3d-models/microbit-v2-759eb0f3db0d44d5a7ea80d4ae00580e)   
[<img width="926" height="599" alt="image" src="https://github.com/user-attachments/assets/65bf2a22-e685-43e6-a0a4-6368b75d029f" />](https://sketchfab.com/3d-models/microbit-v2-759eb0f3db0d44d5a7ea80d4ae00580e)       [<img width="1090" height="697" alt="image" src="https://github.com/user-attachments/assets/79e08459-a4f7-41b8-a450-8f13bd78e6ed" />](https://sketchfab.com/3d-models/microbit-v2-759eb0f3db0d44d5a7ea80d4ae00580e)     
Buy: [Cult3D](https://cults3d.com/en/3d-model/various/micro-bit-v2)  

---

## SVG

Micro:bit fournit de beaux SVG et images du Micro:bit V2.   

[<img width="971" height="625" alt="image" src="https://github.com/user-attachments/assets/9048e1c5-c50d-4357-b94d-5d2dc7a624d3" />](https://microbit.org/design-your-microbit/v2/)   
[<img width="1125" height="510" alt="image" src="https://github.com/user-attachments/assets/e82f9ec1-d65c-480f-b7ff-bc56cfdebb8e" />](https://microbit.org/design-your-microbit/v2/)  
[Site Web officiel](https://microbit.org/design-your-microbit/v2/) - [GitHub](https://github.com/microbit-foundation/microbit-svg)  

---

## Un moteur et des roues ?

Si vous avez envie de faire un petit jeu de voiture avec votre prototype, ce moteur est l’un des plus achetés sur le web :   
  
[<img width="516" height="516" alt="image" src="https://github.com/user-attachments/assets/b0afd70e-f8aa-4999-b73f-7a944e3b7a9a" />](https://cults3d.com/en/3d-model/gadget/zdkderphb)     
[https://cults3d.com/en/3d-model/gadget/zdkderphb](https://cults3d.com/en/3d-model/gadget/zdkderphb)     



--------

## Micro:Bit dans Scratch

Pour vous inspirer des fonctionnalités à créer avec votre Micro:Bit virtuel :
Voici les actions disponibles pour les enfants dans Scratch

<img width="572" height="496" alt="image" src="https://github.com/user-attachments/assets/e8bd4620-c4af-475a-8480-4dae1712a95f" />

* When A, B, or Any button pressed
* Display Icon
* When pin 0, 1, or 2 connected (touched)
* Clear Display
* When tilted (Front, Left, Right, Back)
* Variable: tilt angle (Front, Left, Right, Back)
* Condition:
  * A, B button pressed
  * Is tilt (Front, Left, Right, Back)?

---------------

# Challenge de bourrin ;)

Créer une communication Bluetooth entre le Micro:bit et votre Quest 3.  

C’est du vrai portfolio.  

Si vous réussissez cet exercice en plus de connecter le casque en Bluetooth avec votre simulateur…   
GG, vous serez adoré·e dans la communauté Scratch ;)   


-------------



# Acheter un Micro:bit ?

[<img width="1391" height="468" alt="image" src="https://github.com/user-attachments/assets/5e5d86d8-f402-4b26-bd5e-e642f769e0ec" />](https://www.kiwi-electronics.com/nl/bbc-microbit-v2-2-go-bundel-10260)    
https://www.kiwi-electronics.com/nl/bbc-microbit-v2-2-go-bundel-10260    

[<img width="1206" height="710" alt="image" src="https://github.com/user-attachments/assets/db1229e6-06f4-468f-9209-8415c01e0da5" />](https://www.amazon.com.be/-/en/KEYESTUDIO-Microbit-Sensor-Starter-except/dp/B07GSVHWNS/)    
https://www.amazon.com.be/-/en/KEYESTUDIO-Microbit-Sensor-Starter-except/dp/B07GSVHWNS/    



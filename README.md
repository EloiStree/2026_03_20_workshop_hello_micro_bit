> 🎥: Youtube | 🐙: GitHub  | 💾: Commit de solution  | 📝: Faites-le vous-même | 📕: Manuel    


> Quatre semaine en une ligne pour la formation en cours:  
`Brackey 2D > Quest3 2D App > Godot XR Tool > Grab + Snap > Led > Button > Mod > Sensor > Group work > Jam`  
> Cours: https://github.com/EloiStree/2026_05_11_workshop_hello_godot_xr/blob/main/README.md  


**Apprendre à créer un Micro:Bit puis l'utiliser avec Godot XR Tools**

* Avant l'atelier :
  * Faire le tutoriel de Brackeys sur la 2D [🎥](https://www.youtube.com/watch?v=LOhfqjmasi0)  
  * Pratiquer un peu Git et GitHub pour connaître les bases. [🐙](https://github.com/EloiStree/HelloGit/issues)
  * Jetez un coup d'oeil à la doc de GDScript [📕👁️](https://docs.godotengine.org/en/stable/tutorials/scripting/gdscript/gdscript_basics.html)
  * Un jeu, c'est des cubes et des ronds... C'est quoi un cube ? [🎥🐷](https://youtu.be/fT_yVg7_ECg?t=6)
  * Rotation et Translation... bougeons un drone Unity3D a Godot 🛸 => [Soon]
  * Des cubes et des ronds... prototypons des Micro Bit Sensor en Group avec Git 🧊 => [Soon]
* Allons faire un simple cube pour le fun d’apprendre Godot [🎥](https://www.youtube.com/watch?v=tbfzr3zpOBc)  

**Chapitre 1: Creer le Micro:Bit**
* **Créer** une LED avec un script pour changer la couleur [💾](https://github.com/EloiStree/2026_03_20_godot_hello_micro_bit#103e56528e9f722b197b621eaf7b78569963ac0e) [🎥](https://www.youtube.com/watch?v=jsYthLYksqA&t=46s) [📝](https://github.com/EloiStree/2026_03_20_workshop_hello_micro_bit/blob/main/start_from/E0_LED.md)
* **Sauver le projet** avec Git [🎥](https://www.youtube.com/watch?v=OgYPy7lx0Ro)
* **Créer un tableau de LED 5x5** avec la scène de LED [💾](https://github.com/EloiStree/2026_03_20_godot_hello_micro_bit#c9bd120a0b8e7554180fdbd6058c06cf72b16a36) [🎥](https://youtu.be/Tq3iMY05yEE)
[📝](https://github.com/EloiStree/2026_03_20_workshop_hello_micro_bit/blob/main/start_from/E3_ARRAY.md)
* **Button A et B Basic**
  * Un Script et une Scene [💾](https://github.com/EloiStree/2026_03_20_godot_hello_micro_bit.git#ae27e5571bee337a4c3ca35a6a6261cbdfa13937) [🎥](https://youtu.be/rpCgu9PUcPM)
  * Area3D et input_event [💾](https://github.com/EloiStree/2026_03_20_godot_hello_micro_bit.git#b6d4fce5317db19a8029eb6a166a9a338dfede8e) [🎥](https://youtu.be/LmxfQG9vquw)
  * Area3D et entered exited [💾](https://github.com/EloiStree/2026_03_20_godot_hello_micro_bit.git#b6d4fce5317db19a8029eb6a166a9a338dfede8e) [🎥](https://youtu.be/1d7KVKP9QE0)
    * Layer vs Group vs Tag Script [💾](https://github.com/EloiStree/2026_03_20_godot_hello_micro_bit.git#9d12e11087c3a35f9c7ca3aff71f3f9ac217195f) [🎥](https://youtu.be/6-n_pRp8_i8)
  * **.svg** pour notre Micro:Bit et ... [💾](https://github.com/EloiStree/2026_03_20_godot_hello_micro_bit.git#356a22664ee4016f28b99a15702bec97d135292e) [🎥](https://youtu.be/yXuJRLHk99U)
* ... Fusion 😋🔥 [💾](https://github.com/EloiStree/2026_03_20_godot_hello_micro_bit.git#356a22664ee4016f28b99a15702bec97d135292e)  [🎥](https://youtu.be/yXuJRLHk99U)
* De fait... C est compliquer le modding ?
  * Un premier Hello World `load(path)` [💾](https://github.com/EloiStree/2026_03_20_workshop_hello_micro_bit.git#3c63b1667446e72808ef4c70e806c5e2eb426cc9) [~🎥 V0~](https://youtu.be/RA2AoSgYbLA) [🎥 V1](https://youtu.be/ircNOqSR-Hs) [🐙](https://github.com/EloiStree/HelloGodotModding/blob/main/README.md)
  * Modder avec call method , set variable et connect signal [🎥](https://youtu.be/mRmOX5L-EvA)

> ⌛ Pour aller plus loin dans l'exercice, cela demande un trop gros niveau de programmation.
> Je me permets donc de coder le reste. On utilisera donc le Micro:bit que je vous donnerai à disposition pour la suite:
> `git clone https://github.com/EloiStree/2026_03_20_gdp_hello_micro_bit.git addons/2026_03_20_gdp_hello_micro_bit`
> Je vous invite, comme challenge, à faire un mini-jeu avec ce que l'on a créé jusque ici, sans les pins et les senseurs.


**Chapitre 2 : Godot XR et Toolkit**

* [ ] Comment setup le projet pour la XR ?
  * [ ] Refaire les étapes sur le casque ?
* [ ] Écouter les inputs des manettes ?
  * [ ] Sur PC ?
  * [ ] Sur Quest ?
  * [ ] Écouter la manette "Xbox" ?
* [ ] Interagir sans boîte à outils ?
  * [ ] Toucher des objets ?
  * [ ] Viser un objet Godot Spring ?
    * [ ] Challenge : temps d’interaction ?
* [ ] La flemme, allons sur Godot XR Toolkit
  * [ ] Comment l’installer ?
  * [ ] Attraper un objet ?
  * [ ] Snapper un objet ?
  * [ ] D’autres interactions ?
  * [ ] Snapper le Micro:bit ?
    * [ ] Ouvrir la doc sur une page web si "?" est touché ?
  * [ ] Le clipboard sur Quest pour charger du code ?
    * [ ] Créer un bouton Clipboard → Micro:bit ?


**Chapitre 3 : Créer des boîtes à outils**

Je liste ici une centaine de senseurs et objets IoT avec de la documentation :

* [https://github.com/EloiStree/2026_03_23_doc_micro_bit_sensor](https://github.com/EloiStree/2026_03_23_doc_micro_bit_sensor)

Vous pouvez trouver mes solutions ici :

* [https://github.com/EloiStree/2026_04_11_gdp_learn_with_sensors](https://github.com/EloiStree/2026_04_11_gdp_learn_with_sensors)

Nous allons pratiquer deux concepts en groupe :
* Le grayboxing par contribution (fork) sur GitHub
* La création de boîtes à outils en solitaire (addons)
  
Dans notre projet est ajouté cet addon de boîte à outils que j’ai fait pour l’occasion :   
https://github.com/EloiStree/2026_04_12_gdp_vibed_laser_cut_shader  
_Essayez de faire des projets open source qui seraient fabricables en FabLab._  


**Chapitre 4 : Utiliser le Micro:bit**

On a des senseurs et un micro:bit fonctionnel.
Essayons de faire des mini-jeux pour apprendre l’électronique.
On ignore le câblage et la réalité de l’électricité dans cet exercice.

Jouons avec les LED et relions les pins du micro:bit en pourcentage à des senseurs et moteurs eux aussi en pourcentage.


**Challenge**:
- Prendre en main le plug-in: Godot Aerodynamic Physics
  - https://github.com/EloiStree/2026_03_23_doc_micro_bit_sensor/issues/107 


**Nouveau depart**:
> On a un Micro:bit avec un facade 🫡.   
-  Regardons ou on en est niveau de GDScript [📕👁️](https://docs.godotengine.org/en/stable/tutorials/scripting/gdscript/gdscript_basics.html)
-  Regardons ou on en est en C# , ou en Rust


Une fois le Micro:bit fait hors de la VR:
* Faire un Cube dans le casque [🎥](https://www.youtube.com/watch?v=yMFC_DTZ0fQ)
* C est quoi un casque VR ? [🎥](https://www.youtube.com/watch?v=tweBgb79VyE&t=292s)
* Allons plus loin dans ce qu'est la VR en general [🎥](https://github.com/EloiStree/HelloOneDayGodotXR/tree/main)
* Pratiquons Godot XR Tools [🎥](https://github.com/EloiStree/HelloGodotXR/issues/25)
  * Pick
  * Snap 


Exercice:  
- Pratiquez les rotations:
  - https://github.com/EloiStree/2026_03_20_workshop_hello_micro_bit/issues/2
    - Simuler le tilt face vers le haut
    - Simuler le tilt en format volant de voiture
    - Simuler un jeu de dee avec le Micro:Bit
    - Simuler un accelerometer en Vector3
  - Simuler un compass vers un faux nord en VR.  


Git Additionnel:
- Croco Color:  https://github.com/EloiStree/2026_03_30_gdp_croco_color_xr.git
- Micro Bit Keyestudio Sensor https://github.com/EloiStree/2026_03_23_gdp_micro_bit_sensor
  
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



-------------------

# PINS

[<img width="720" height="699" alt="image" src="https://github.com/user-attachments/assets/a1321e93-871b-4e20-9417-e9bc6e8a237c" />](https://microbit-micropython.readthedocs.io/en/latest/pin.html)   
https://microbit-micropython.readthedocs.io/en/latest/pin.html   




# Linked Package

- CNC Shader: https://github.com/EloiStree/2026_04_12_gdp_vibed_laser_cut_shader


# PINCH · ORBIT — Les Éclats d’Astra

Un escape game orbital, un peu magique, où vos mains deviennent les commandes. Explorez l’arche, collectez les reliques et ouvrez la Porte des Astres.

**Version 2.3.0 :** envoyez les souvenirs et transmissions hors de l’écran d’un balayage de la main ouverte, vers la gauche ou la droite. Les panneaux accompagnent votre geste avant de disparaître.

**Nouveau dans la version 2.2.2 :** recherche des mains éloignées dans des zones agrandies, suivi des deux mains plus stable et aperçu de calibration agrandi avec compteur. PINCH demande une image HD si la webcam le permet ; la portée réelle dépend aussi de l’éclairage et du matériel.

### Caméra utilisée dans une autre application

La version 2.2.1 ajoute un lecteur Windows en **lecture partagée**, essayé automatiquement si la webcam par défaut est occupée. Le sas permet aussi de choisir directement ce mode ou une caméra virtuelle installée. Les images restent sur votre PC ; aucun microphone n’est demandé.

Si le pilote refuse encore le partage : **Paramètres Windows → Bluetooth et appareils → Caméras → votre caméra → Options avancées → Autoriser plusieurs applications à utiliser la caméra** (Windows 11 récent, selon disponibilité). Une caméra virtuelle ou une seconde webcam reste nécessaire avec certains pilotes exclusifs. [Explications Microsoft](https://support.microsoft.com/en-us/windows/hardware/camera/manage-cameras-with-camera-settings-in-windows-11).

[**Télécharger pour Windows 64 bits**](https://github.com/Toka120/PINCH/releases/latest/download/PINCH-Portable.exe)

![ORBIT — Les Éclats d’Astra](https://github.com/Toka120/PINCH/releases/download/v2.2.0/ORBIT.png)

## Une station qui a des choses à raconter

Astra s’est isolée pour protéger des refuges de la **Marée blanche**, une anomalie qui efface les chemins entre les étoiles. **Élye**, une présence née des messages laissés par les voyageurs, vous accompagne. En explorant, vous découvrirez les traces des deux sœurs Venn et du cartographe Naël.

La version enrichie ajoute **13 souvenirs**, **8 transmissions**, **trois fragments cachés** et un épilogue facultatif. Les secrets ne bloquent pas la sortie principale et restent accessibles après une première fin. Le journal sépare les indices des mémoires ; on peut tourner ses pages et relire les messages avec l’index posé.

![Un souvenir d’Astra](https://github.com/Toka120/PINCH/releases/download/v2.2.0/MEMOIRES.png)

## Vos gestes font le jeu

- **Posez l’index sur une commande environ 0,75 seconde** : l’anneau se remplit et le bouton s’active. Retirez le doigt de la zone avant de recommencer.
- **Pincez** pour saisir un objet et déplacez votre main pour le transporter.
- **Glissez dans le sac**, puis ouvrez les doigts pour ranger la relique.
- **Reprenez depuis le sac**, puis déposez l’objet sur un emplacement de lumière pour l’utiliser.

La carte, le journal, les runes et les passages suivants sont activables par l’index posé. Une mauvaise utilisation ne détruit pas vos objets et une perte de suivi ne fait pas disparaître une relique du sac.

## Une aventure entre les étoiles

Cinq lieux à découvrir et à revisiter :

- Le **Sas des Échos**, cœur endormi de la station.
- Le **Jardin des Comètes**, où poussent les cristaux d’éther.
- Les **Archives Lunaires**, gardiennes des trois runes.
- L’**Observatoire**, qui se souvient du ciel.
- La **Porte des Astres**, dernier voile avant la liberté.

Le journal conserve les indices ; le sac et les énigmes résolues sont sauvegardés sur votre PC. Ce premier épisode possède une fin et peut être rejoué. Les ateliers Construction, Précision et Jeu libre, ainsi que les cinq exercices historiques, restent dans le même EXE.

## Avant de jouer

Téléchargez **PINCH-Portable.exe**, lancez-le et cliquez sur **Activer ma caméra**. Une **calibration obligatoire** des pinces, de l’espace et de la précision précède chaque session. Pour continuer après une étape validée, gardez l’index sur le bouton Continuer ou cliquez dessus.

Windows 64 bits, webcam et éclairage suffisant. Aucune installation et aucune connexion Internet nécessaires pour jouer. Après calibration, souris et tactile restent possibles si la caméra est arrêtée. Les objets sont affichés en 3D et déplacés sur un plan face à vous.

La vidéo est traitée sur votre PC, sans enregistrement ni envoi. L’EXE n’est pas signé numériquement ; Windows peut afficher un avertissement. Les tests vérifient la calibration simulée, les gestes, les interactions et le scénario ; le suivi réel dépend de la webcam et de l’éclairage.

Suivi : MediaPipe Tasks Vision. Rendu : Three.js. Application : Electron. Fond spatial généré pour ORBIT.

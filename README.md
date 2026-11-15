# PINCH · ORBIT

Un atelier spatial 3D où vos mains deviennent les commandes. Pincez le pouce et l’index pour attraper les objets, déplacez-les, puis ouvrez les doigts pour les relâcher.

[**Télécharger ORBIT pour Windows 64 bits**](https://github.com/Toka120/PINCH/releases/latest/download/PINCH-Portable.exe)

![La station ORBIT](https://github.com/Toka120/PINCH/releases/download/v2.0.0/ORBIT.png)

## Avant le décollage

1. Téléchargez **PINCH-Portable.exe** et lancez-le directement. Aucune installation nécessaire.
2. Cliquez sur **Activer ma caméra** dans le sas de préparation.
3. Calibrez vos pinces, votre espace de mouvement et votre précision. Chaque étape validée passe automatiquement à la suivante.
4. Les trois portails s’ouvrent : choisissez librement votre activité.

**La calibration est obligatoire avant chaque session.** Une webcam et un endroit éclairé sont nécessaires. Les réglages et la progression sont sauvegardés sur votre PC.

## Votre station, votre rythme

| Activité | Objectif |
| --- | --- |
| Construction | Réassemblez les fragments de la balise orbitale |
| Précision | Placez les objets dans leurs orbites et stabilisez vos gestes |
| Jeu libre | Manipulez et composez librement avec cinq objets |

Les emplacements aimantés aident à stabiliser les placements. Les missions réussies rapportent de la poussière d’étoiles et leurs placements varient. Les objets sont rendus en 3D et déplacés sur un plan face à vous ; la profondeur n’est pas contrôlée par la webcam.

Les cinq exercices historiques restent disponibles via **Entraînement**, dans le même EXE. Après calibration, souris et tactile restent possibles si vous arrêtez la caméra. Les sons sont facultatifs et désactivés au départ.

## Configuration et confidentialité

Windows 64 bits, webcam, rendu WebGL 2. L’application fonctionne hors ligne et n’a pas besoin de Node.js ou d’un navigateur installé.

Le traitement des mains se fait sur votre PC. L’application n’enregistre pas et n’envoie pas la vidéo. Le bouton caméra permet de l’arrêter. En cas de refus, autorisez la caméra pour les applications de bureau dans les paramètres de confidentialité Windows.

Cette première V1 n’est pas signée numériquement : Windows peut afficher un avertissement. Les tests automatisés vérifient le rendu, la calibration simulée et les interactions ; le confort réel dépend de votre webcam et de l’éclairage.

Suivi : MediaPipe Tasks Vision. Rendu 3D : Three.js. Application Windows : Electron. Fond spatial généré pour ORBIT.

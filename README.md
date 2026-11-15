# PINCH — Le jeu entre vos mains

Un petit jeu Windows où votre webcam transforme vos mains en contrôleurs : pincez le pouce et l’index pour attraper les carrés, déplacez-les, puis relâchez.

**Version 1.3.2** : correction des cibles de calibration de l’espace. Placez l’index dans le cercle, pincez 0,2 seconde, puis ouvrez les doigts. La pince peut commencer avant d’entrer dans le cercle. Le suivi stabilisé, l’aimantation du niveau 005 et les réglages existants sont conservés.

## Télécharger et jouer

[**Télécharger PINCH pour Windows 64 bits**](https://github.com/Toka120/PINCH/releases/latest/download/PINCH-Portable.exe)

Ouvrez **Releases** sur ce dépôt, puis téléchargez **PINCH-Portable.exe** dans les fichiers de la version la plus récente. Les archives « Source code » ne contiennent pas l’application Windows.

1. Double-cliquez sur **PINCH-Portable.exe**. Aucune installation nécessaire.
2. Cliquez sur **Activer la caméra**.
3. Commencez au **niveau 003** pour calibrer vos mains, puis passez aux niveaux suivants.

Configuration : Windows 64 bits, webcam et éclairage suffisant. L’application fonctionne hors ligne ; vos amis n’ont pas besoin d’installer Node.js ou un navigateur.

## Les cinq niveaux

| Niveau | Activité |
| --- | --- |
| 001 | Une main, un carré à attraper |
| 002 | Deux mains, deux carrés indépendants |
| 003 | Cinq cycles ouvrir, pincer, relâcher par main |
| 004 | Calibration de votre espace de mouvement confortable |
| 005 | Placement précis des deux carrés et relâchement séparé |

Les réglages sont conservés localement sur votre PC. Le bouton **Refaire la calibration** permet de recommencer. Gardez une distance similaire à la caméra après calibration.

## Caméra et confidentialité

Le traitement vidéo se fait sur votre PC. L’application n’enregistre pas et n’envoie pas les images de la webcam. **Arrêter la caméra** coupe la vidéo.

Si la caméra est refusée, vérifiez l’autorisation d’accès à la caméra pour les applications de bureau dans les paramètres de confidentialité Windows. Une seule caméra est utilisée ; la souris ou le tactile permettent aussi de déplacer les carrés, mais la calibration nécessite vos mains devant la webcam.

## Version de démonstration

L’exécutable n’est pas signé numériquement ; Windows peut donc afficher un avertissement. La détection peut être moins fiable lorsque les mains se croisent, sortent du champ ou sont mal éclairées. Les tests automatiques vérifient les interactions et les gestes simulés ; la précision réelle dépend de votre webcam.

Le suivi des mains utilise MediaPipe Tasks Vision (Google). L’application Windows utilise Electron.

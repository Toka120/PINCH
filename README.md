# Sensory — Les Éclats d’Astra

### Une aventure MirorStudio · Vos mains sont la clé

<p align="center"><img src="assets/mirorstudio-logo.svg" width="120" alt="MirorStudio"></p>

![Sensory — une main translucide saisit une relique devant l’arche orbitale d’Astra](assets/sensory-opening.png)

*Illustration d’ambiance de Sensory ; ce visuel n’est pas une capture du jeu.*

Pour protéger les refuges de la **Marée blanche**, Astra a choisi le silence. À bord de l’arche orbitale, des reliques attendent de retrouver leur place. Guidé par **Élye**, explorez les lieux, reliez les indices et rouvrez le passage vers les étoiles.

**Sensory** est un escape game orbital joué avec les mains devant une webcam : pincez pour saisir, déplacez les reliques et utilisez-les ailleurs dans la station. Les mains holographiques font le lien entre vos gestes et le monde du jeu.

[**Télécharger Sensory pour Windows 64 bits**](https://github.com/Toka120/PINCH/releases/latest/download/PINCH-Portable.exe)

Aucune installation nécessaire. Le fichier distribué conserve le nom `PINCH-Portable.exe` pour garder le lien de téléchargement existant ; vous pouvez le renommer **Sensory.exe**.

### Préversion Unity : le suivi des mains en priorité

[**Essayer le Seuil de Résonance dans Unity pour Windows**](https://github.com/Toka120/PINCH/releases/download/v3.0.0-preview.3/PINCH-Portable.exe)

La migration a commencé : sas obligatoire, deux mains articulées, relique à saisir, sac et couronne aimantée. Le suivi natif tourne indépendamment du rendu, avec un repère vidéo constant, des identités persistantes, une pince mesurée en 3D estimée et un diagnostic visible. Il utilise toujours MediaPipe ; les doigts occultés et certaines rotations restent difficiles avec une webcam.

Dans la nouvelle entrée, **pincez deux prises de lumière, puis écartez les mains** : une fenêtre s’ouvre sur la scène 3D d’Astra. L’ouverture reste acquise quand vous relâchez ou perdez une main. Une pause, des sons réactifs et un souvenir facultatif accompagnent le geste. Relâchez et posez l’index sur **Traverser le passage** pour rejoindre la salle de l’éclat.

**Toute l’aventure n’est pas encore portée dans Unity.** Le pupitre central permet d’ouvrir la version complète 2.4.1 embarquée, avec ses sauvegardes et ses exercices. Le suivi natif concerne le Seuil et la salle Unity. L’introduction garde le logo officiel MirorStudio. [Lire les détails de la préversion](https://github.com/Toka120/PINCH/releases/tag/v3.0.0-preview.3).

## Vos gestes font le jeu

- **Pincez le pouce et l’index** pour saisir une relique, puis déplacez votre main pour la transporter.
- **Ouvrez les doigts** pour la relâcher ou la ranger dans le sac orbital.
- **Reprenez une relique du sac** et utilisez-la sur un mécanisme dans un autre lieu.
- **Posez l’index environ 0,75 seconde sur une commande** : un anneau se remplit, puis le bouton s’active. Retirez le doigt avant de recommencer.
- **Balayez avec la main ouverte** pour fermer les souvenirs, les transmissions et les épilogues.

Le bouton **Commandes**, au centre du terrain, ouvre une console à quatre grandes cases. Une mauvaise utilisation ne détruit pas vos reliques ; la progression est sauvegardée sur votre PC.

## Une arche à explorer

Cinq lieux reliés, à découvrir et à revisiter :

- Le **Sas des Échos**, cœur endormi de la station.
- Le **Jardin des Comètes**, où poussent les cristaux d’éther.
- Les **Archives Lunaires**, gardiennes des trois runes.
- L’**Observatoire**, qui se souvient du ciel.
- La **Porte des Astres**, dernier voile avant la liberté.

Élye est une présence née des messages librement confiés à la station. Les traces des sœurs Iria et Mara Venn et du cartographe Naël accompagnent votre exploration.

Le journal conserve les indices ; le sac et les énigmes résolues sont sauvegardés. **13 souvenirs, 8 transmissions, trois fragments cachés et un épilogue alternatif** enrichissent l’aventure. Les secrets restent facultatifs et accessibles après la fin normale.

Les ateliers **Construction**, **Précision** et **Jeu libre**, ainsi que les **cinq exercices historiques** accessibles par Entraînement, restent dans la même application.

## Avant de jouer

Lancez Sensory, découvrez le générique **MirorStudio** et le synopsis, puis cliquez sur **Commencer le voyage**. Activez la caméra et effectuez la **calibration obligatoire à chaque session** : vos pinces, votre espace, votre précision. Après chaque étape validée, posez l’index sur **Continuer** ou cliquez sur le bouton.

**Windows 64 bits, webcam et éclairage suffisant.** Aucune connexion Internet nécessaire pour jouer. Après calibration, souris et tactile restent possibles si la caméra est arrêtée. Les objets sont affichés en 3D et déplacés sur un plan face à vous.

La vidéo est traitée sur votre PC, sans enregistrement ni envoi. Aucun microphone n’est demandé. Le suivi d’une caméra unique reste une estimation : sa qualité dépend de la webcam, de l’éclairage et des doigts masqués.

### Si la caméra est déjà utilisée

Sensory essaie un lecteur Windows en **lecture partagée** si la webcam par défaut est occupée. Le sas permet aussi de sélectionner cette source ou une caméra virtuelle installée. Certains pilotes exclusifs empêchent encore le partage ; une autre webcam ou une caméra virtuelle peut alors être nécessaire.

Sur les versions Windows compatibles, les paramètres de caméra peuvent proposer une option multi-application. [Explications Microsoft](https://support.microsoft.com/en-us/windows/hardware/camera/manage-cameras-with-camera-settings-in-windows-11).

L’EXE n’est pas signé numériquement ; Windows peut afficher un avertissement.

## Dernières améliorations

**2.4.1** — Validation des paumes et poignets, confirmation des nouvelles mains sur plusieurs images et regroupement renforcé des doubles détections avant la calibration.

**2.4.0** — Mains holographiques articulées en 3D, identités plus stables après de courtes pertes de suivi et console centrale à quatre grandes commandes.

**2.3.0** — Fermeture des souvenirs et transmissions par balayage de la main ouverte.

---

**Sensory · MirorStudio**  
Suivi : MediaPipe Tasks Vision · Rendu : Three.js · Application : Electron.  
Ancien nom du projet : PINCH ORBIT. Le dépôt et le nom de l’artefact de distribution sont conservés pour la continuité des liens.

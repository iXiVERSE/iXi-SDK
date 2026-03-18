# iXi-SDK
Code source pour le développement d'applications XR basées sur le standard iXi.  
Notre code est sous licence MPL 2.0, ce qui permet une réutilisation commerciale ou non.
## Description
iXi-SDK est un ensemble d'outils open source destinés 
- à la création de contenus spatialisés via **iXiMAKER "Mini"** :
  - Version "Work" pour les procédures (process techniques)
  - Version "Learn" pour les quizz en lien avec les procédures
- à la création d'applcations (XR/AR/VR/3D/2D) via le code C# pour Unity 3D.
## Mode créateur
Les créateurs de contenus, peuvent simplement utiliser iXiMAKER "mini" pour générer facilement des fichiers JSON iXi compatibles avec iXiWORK.
### Prérequis
- **✨ iXiMAKER "mini" Work** (pour les process)
- **✨ iXiMAKER "mini" Learn** (pour les quizz)
- **🥽 iXiWORK** : le player XR gratuit pour Meta Quest3/3s et Pico Ultra
- **🖼️ Vos médias** (images / Audio / Modèles 3D) pour vos contenus
> ℹ️ Vous pouvez [télécharger la version licenciée **gratuite** d'iXiWORK ici](https://ixiverse.com)👈
## Mode développeur
Le code source C# pour Unity 3D gère l'interprétation des contenus iXi au sein d'Unity 3D.  
Il simplifie sont intégration et son utilisation.
### Prérequis
- 🗃️ iXi-CODE (Code source C# pour unity)
### Prérequis technique conseillé
- 📦 Unity (6000.3.8f1)
  - Universal Render Pipeline (17.3.0) > Création de textures
  - Unity glTFast (6.14.1) > Import de fichiers 3D au format GLTF/GLB
  - KTX for Unity (3.6.3) > Import des textures GLTF/GLB
  - Newtonsoft Json > Serialisation / Déserialisation Json
  - Sentis (2.5.0) > Processeur de voix (ONNX / IA)
  - Pipper
  - SharpZipLib (1.4.1) > Import de fichier ZIP
  > **Pour la création d'un player VR/XR, ajouter les packages suivants :**
  >> -  AR Foundation (6.4.1)
  >> -  Google AR Core XR Plugin (6.3.3)
  >> -  OpenXR plugin (1.16.1)
  >> -  Unity OpenXR Meta (2.4.0) (Pour Quest 3 et 3s) / PICO Unity OpenXR SDK  (Pour Pico 4 et 4 Ultra)
  >> -  XR Composition Layers (2.3.0)
  >> -  XR Core Utilities (2.5.3)
  >> -  XR Hands (1.7.3)
  >> -  XR Interaction Toolkit (3.3.1)

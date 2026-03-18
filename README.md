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
- **🥽 iXiWORK** : le player XR pour Meta Quest3/3s ou Pico Ultra
- **🖼️ Vos médias (images / Audio / Modèles 3D) pour vos contenus
> ℹ️ Vous pouvez [télécharger la version gratuite d'iXiWORK ici](https://ixiverse.com)👈
## Mode développeur
Le code source pour Unity 3D gère l'interprétation des contenus iXi au sein d'Unity 3D.  
Il permet de simplifier l'utilisation 
### Prérequis technique conseillé
- Unity (6000.3.8f1)
  - Universal Render Pipeline (17.3.0) (Conversion des textures GLTF)
  - Unity glTFast (6.14.1) > Import de fichiers 3D au format GLTF/GLB
  - KTX for Unity (3.6.3) > Import des textures GLTF/GLB
  - Newtonsoft Json > Serialisation / Déserialisation Json
  - Sentis (2.5.0) > Processeur de voix (ONNX / IA)
  - SharpZipLib (1.4.1) > Import de fichier ZIP

# MediScan Pro - Scanner de Carte d'Assurance

Une application Web monopage (SPA) intelligente pour scanner, extraire et enregistrer automatiquement les données des cartes d'assurance sans intervention humaine.

## Fonctionnalités

*   **Vision par Ordinateur (OpenCV.js)** : Détection automatique des contours de la carte et redressement de perspective (Warp Perspective).
*   **OCR Intelligent (Tesseract.js)** : Extraction automatique du texte (Nom, Police, N° Assuré, etc.).
*   **Expérience "Zéro Clic"** : Capture automatique lorsque la carte est stable, feedback visuel et sonore, et réinitialisation automatique.
*   **100% Client-Side** : Fonctionne entièrement dans le navigateur sans backend complexe requis pour le traitement d'image.

## Comment utiliser

1.  Clonez ce dépôt.
2.  Ouvrez le fichier `index.html` dans un navigateur moderne (Chrome, Edge, Firefox).
    *   *Note : Pour des raisons de sécurité liées à l'accès caméra, il est recommandé d'utiliser un serveur local (ex: Live Server sur VS Code ou `npx serve`).*
3.  Autorisez l'accès à la webcam.
4.  Présentez une carte d'assurance devant la caméra.

## Technologies

*   HTML5 / CSS3 (Design moderne et responsive)
*   JavaScript (ES6+)
*   [OpenCV.js](https://docs.opencv.org/4.x/d5/d10/tutorial_js_root.html) (Traitement d'image)
*   [Tesseract.js](https://tesseract.projectnaptha.com/) (OCR)

## Auteur

Projet réalisé par un expert Full-Stack JavaScript & Vision par Ordinateur.

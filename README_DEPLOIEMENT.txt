FGE TEST iPhone/iPad — PWA GitHub Pages
=======================================

CONTENU
- index.html : test candidat, 100 questions, 20 s/question
- manifest.webmanifest : installation sur écran d’accueil
- sw.js : fonctionnement hors ligne après première ouverture
- icons/ : icônes PWA/iOS
- .nojekyll : empêche le traitement Jekyll inutile sur GitHub Pages

DÉPLOIEMENT RAPIDE SUR GITHUB PAGES
1. Créer un dépôt PUBLIC sur GitHub, par exemple : fge-test-1rs-ios
2. Ajouter TOUS les fichiers et le dossier icons/ À LA RACINE du dépôt.
3. Ouvrir Settings > Pages.
4. Dans Build and deployment :
   Source = Deploy from a branch
   Branch = main
   Folder = /(root)
   puis Save.
5. Attendre la publication. GitHub affichera l’URL du site.
   Elle sera généralement :
   https://VOTRE-IDENTIFIANT.github.io/fge-test-1rs-ios/
6. Ouvrir cette URL sur l’iPhone dans Safari.
7. Safari > Partager > Sur l’écran d’accueil > Ajouter.
8. Lancer l’icône créée et effectuer un test de partage d’un fichier .fger.

IMPORTANT
- Le dépôt et le site GitHub Pages sont publics avec GitHub Free.
- Le test ne transmet ni ne stocke de résultat sur GitHub : le résultat .fger est créé localement
  en mémoire puis transmis par la feuille de partage du navigateur.
- Après une première ouverture réussie, le service worker met en cache l’application pour un usage hors ligne.
- Pour une nouvelle version, remplacer les fichiers dans le dépôt. Si nécessaire, augmenter CACHE dans sw.js
  (par exemple fge-test-1rs-pwa-v2) afin de forcer le renouvellement du cache.


V2 : traditions/culture Spahis + identification, schema .fger v4. Remplacer les fichiers du dépôt GitHub Pages par le contenu de ce ZIP.

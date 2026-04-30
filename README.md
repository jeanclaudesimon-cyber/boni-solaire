# FICHE MÉMO : Publier une page web sur GitHub Pages

But : Mettre en ligne un fichier index.html pour avoir un lien https://... gratuit

## ÉTAPE 1 : Créer le dépôt
1. Va sur https://github.com/new
2. Nom du dépôt : mon-site ou ce que tu veux, sans espace ni accent
3. Coche Public
4. Coche Add a README file
5. Clique Create repository

## ÉTAPE 2 : Ajouter ta page
1. Dans le dépôt, clique Add file > Upload files
2. Glisse ton fichier index.html
3. En bas clique Commit changes

Important : Le fichier DOIT s'appeler exactement index.html avec un i minuscule.

## ÉTAPE 3 : Activer la mise en ligne
1. Dans ton dépôt, onglet Settings tout à droite
2. Dans le menu à gauche, clique Pages
3. Section Build and deployment :
   - Source : laisse Deploy from a branch
   - Branch : choisis main + dossier /(root) ou /(racine)
4. Clique Save

## ÉTAPE 4 : Récupérer le lien
1. Attends 1-2 min
2. Retourne dans Settings > Pages
3. En haut, cadre vert : Your site is live at https://tonpseudo.github.io/mon-site/
4. C'est ton lien à partager

## Pour mettre à jour ta page :
1. Clique sur index.html dans GitHub
2. Icône crayon Edit en haut à droite
3. Modifie le code > Commit changes
4. Attends 1-2 min, le site est à jour auto

## Pour ajouter d'autres fichiers :
Add file > Upload files > glisse style.css, icon.png, etc.
Puis dans ton index.html tu fais : <img src="./icon.png">

## Pour transformer en appli mobile :
Ajoute ces 3 fichiers en plus : manifest.json, sw.js, icon.png
Et cette ligne dans le <head> de index.html :
<link rel="manifest" href="./manifest.json">

Raccourci mental :
Nouveau repo > Upload index.html > Settings > Pages > main > Lien vert > C'est en ligne.

# OC_P7 - Mon Vieux Grimmoire

Développez le back-end d'un site de notation de livres.

# Etape N°1 - Cloner le projet :

Tout d'abord, nous devons "cloner" le projet, ce qui est une copie du projet sur notre système afin que nous puissions travailler dessus localement.
Rendez-vous sur le repo du projet, cliquez sur le menu déroulant "Code" qui se trouve normalement en haut à droite de l'interface avec une belle couleur verte.
Assurez-vous simplement d'être dans un endroit où cela ne vous dérange pas qu'un nouveau dossier de projet soit ajouté à votre ordinateur, par exemple cd /path/to/folder/hereIsOk

Il vous reste plus qu'a coller le lien du repo après ses deux commandes, comme si-dessous :

`git clone https://github.com/GuillaumeGiordano/Mon-vieux-Grimoire.git`

Vous obtenez un nouveau dossiers `Mon-vieux-Grimmoire`.

# Etape N°2 - Installation :

Ouvrez ce nouveau dossier `Mon-vieux-Grimmoire` dans un éditeur de code (ex: VS Code),
Ouvrez le terminal (ctrl+ ù)
Exécutez la commande `npm install` (ou `npm i`).

REMARQUE : À ce stade, vous verrez une note sur les vulnérabilités, comme nous l'avons abordé dans la dernière section de ce guide. Elle peut indiquer quelque chose comme "trouvé 0 vulnérabilité" (comme dans la capture d'écran ci-dessus), mais il est fort possible que ce nombre soit supérieur à zéro. Si vous voyez des vulnérabilités, ne vous inquiétez pas. Vous êtes libre de les ignorer pour l'instant puisqu'il ne s'agit pas d'un projet que nous avons l'intention de lancer en production pour que d'autres puissent le voir ou l'utiliser.

# Etape N°3 - Configuration :

1/ Création du dossier images dans la racine du projet : Mon-vieux-Grimmoire/`images`
2/ Création et configuration d'un fichier `.env`

# Etape N°4 - Démarrer le serveur :

Si vous jetez un coup d'œil à l'intérieur du fichier package.json du projet cloné, vous verrez la commande permettant de démarrer le serveur de développement `npm start` qui lancera `nodemon server.js`.

REMARQUE : Si votre serveur de développement est toujours en cours d'exécution, vous pouvez l'arrêter avec Ctrl+C.

# Etape N°5 - A vous de jouer :

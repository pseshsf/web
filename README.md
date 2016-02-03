# PSES-HSF

Ce dépôt contient les éléments du site web de PSES, à savoir :
- les fonts
- les fichiers JS
- les images
- les sources SASS permettant de générer les feuilles de styles CSS

Prérequis pour compiler les CSS à partir des SASS
-------------------------------------------------
- installez bundler avec "yaourt -S ruby-bundler" ou "apt install bundler"
- rendez-vous dans le répertoire source : "cd /src"
- installez les dépendances du projet avec "bundle install"

La compilation
--------------
- rendez-vous dans le bon répertoire : "cd src/compass"
- compilez les SASS avec la commande "bundle exec compass compile -e production --force --sourcemap"

Les fichiers CSS seront générés dans le répertoire /assets/css/

Il suffira ensuite les envoyer sur le serveur.

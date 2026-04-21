# Tp2-Git-Maher
# Atelier Pratique 2 : Git et Travail Collaboratif

## Identification:
* Nom : Maher Zouari
* Email Git : maherzouari0@gmail.com

## Objectifs du TP:
Durant cet atelier, j'ai découvert comment travailler avec Git dans un environnement 
collaboratif. Les compétences acquises sont :
* Récupérer un projet distant en le clonant depuis GitHub sur ma machine locale.
* Publier mes modifications sur GitHub via un Push.
* Synchroniser mon travail avec les changements des autres collaborateurs via Fetch et Pull.
* Provoquer et résoudre un conflit de fusion (Merge Conflict) dans VS Code.

## Journal des étapes réalisées:
1. Configuration de l'identité : J'ai configuré mon nom et mon email Git dans 
le terminal de VS Code pour identifier mes commits.
2. Clonage du dépôt : J'ai récupéré le projet `Tp2-Git-Maher` depuis GitHub 
sur mon ordinateur via la commande Git Clone.
3. Modification de participants.md : J'ai ajouté mon nom ainsi que celui 
de mon collaborateur Mehdi Zouari dans le fichier participants.md.
4. Fetch et Pull : J'ai utilisé Fetch pour observer les nouveautés sur GitHub 
puis Pull pour mettre à jour mes fichiers locaux.
5. Simulation et résolution de conflit : J'ai modifié le fichier index.html 
depuis VS Code et depuis GitHub en même temps pour créer un conflit, 
puis je l'ai résolu en choisissant "Accept Both Changes".

## Commandes utilisées:
* `git config --global user.name "Maher Zouari"` : Définit le nom de l'auteur.
* `git config --global user.email "votre-email@gmail.com"` : Définit l'email de l'auteur.
* `git clone <url>` : Télécharge le dépôt distant sur la machine locale.
* `git add <fichier>` : Prépare les fichiers modifiés pour le commit (Staging).
* `git commit -m "message"` : Enregistre les modifications dans l'historique local.
* `git fetch` : Observe les nouveautés sur GitHub sans les intégrer.
* `git pull` : Récupère et fusionne les changements distants sur ma machine.
* `git push` : Envoie mes commits locaux vers GitHub.

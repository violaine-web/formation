# Raccorder un projet créé sur vsc à un compte GitHub

* ouvrir un nouveau terminal dans vsc (ou si le terminal est déjà ouvert déconnecter le serveur en entrant ctrl+c)
* créer le dépôt git à partir des fichiers présents : $ `git init`
* pour ajouter les fichiers présent dans le dépôt local git : $ `git add .`
* ajouter un nœud dans l'hitorique à l'instant t : $ `git commit -m "commit initial"`
* créer un nouveau repository sur GitHub **sans créer de fichier readme**
* pour raccorder le dépôt distant GitHub (qui va être nommé origin) au dépôt local, revenir sur vsc et entrer `git remote add origin git@github.com:violaine-web/yat.git`
* entrer `git branch -M main` pour indiquer qu'il faut tout installer dans la branche principale
* entrer `git push -u origin main` pour transférer tous les éléments
* retourner dans GitHub pour créer un readme pour expliquer le nouveau projet

Et voilà, c'est fait !
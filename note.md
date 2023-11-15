## Dans le cas où on creer un nouveau projet sur github. on suit les démarche pour associer ce nouveau projet a github
- Step 1: sur Terminal, arriver dans le bon dossier, avec le fichier tout prêt à pusher
   - Par avance: Créer l'architecture des fichier (app, data, .eslintrc, .gitignore ), des packages( express ejs dotenv pg etc
- Step 2: Ouvrir Github : créer un répo depuis https://github.com/MeiyinPU?tab=repositories
   - repository name (le même avec le nom du dossier sur Terminal)
   - public
   - valider sans rien d’autre rajouter
- Step 3: Commands sur Terminal : 
   - git init
   - git add .
   - git commit -m "add text"
   - git remote add origin  git@@github.com.....................
   - git push --set-upstream origin master

   Après on peut tourjours utiliser comme d'hab:
    git add .
    git commit -m "update"
  - git push

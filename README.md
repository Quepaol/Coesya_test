# Initialisez un dépôt Git local (si ce n'est pas déjà fait)
git init

# Ajoutez tous vos fichiers au suivi Git
git add .

# Créez une première sauvegarde (commit)
git commit -m "Initial commit - Premier déploiement"

# Liez votre dépôt local à GitHub (remplacez par l'URL de VOTRE dépôt)
git remote add origin https://github.com/votre-username/nom-de-votre-repo.git

# Poussez votre code vers la branche principale (souvent 'main' ou 'master')
git branch -M main
git push -u origin main

echo "# mi_proyecto_git_remoto" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/villecarsi-wq/mi_proyecto_git_remoto.git
git push -u origin main

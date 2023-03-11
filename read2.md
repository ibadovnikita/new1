…or create a new repository on the command line
echo "# new1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ibadovnikita/new1.git
git push -u origin main

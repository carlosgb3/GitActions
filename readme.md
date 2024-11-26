# pasos para crear repo local linked con remoto
…or create a new repository on the command line
echo "# GitActions" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:carlosgb3/GitActions.git
git push -u origin main

…or push an existing repository from the command line
git remote add origin git@github.com:carlosgb3/GitActions.git
git branch -M main
git push -u origin main
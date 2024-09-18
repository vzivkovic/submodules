# submodules


echo "# submodules" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:vzivkovic/submodules.git
git push -u origin main

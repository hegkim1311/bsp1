# bsp1
Branch anlegen und mergen

git switch -c feature-text

echo "Neuer Text" >> README.md

git add README.md
git commit -m "Text ergänzt"

git switch main
git merge feature-text

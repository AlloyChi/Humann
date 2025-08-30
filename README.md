#Humann
git config --global user.name "AlloyChi"
git config --global user.email "chinemerem1421.com"

# create or use an existing repo
mkdir keep-active && cd keep-active
git init
echo "# keep-active" > README.md
git add README.md
git commit -m "docs: add README"
git branch -M main
# create an empty repo on GitHub named keep-active, then:
git remote add origin https://github.com/<YOU>/keep-active.git
git push -u origin main# Humann

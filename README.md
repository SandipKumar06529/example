Create a new repositoryon the command line
echo "# new-repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -m main
git remote add origin git@github.com:SandipKumar06529/example.git
git push -u origin main

Init with https://github.com/lvillen/github-branch-demo

echo "# github-branch-demo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:lvillen/github-branch-demo.git
git push -u origin main

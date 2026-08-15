cd github-actions-demo
git init
git add .
git commit -m "Initial commit"
gh repo create github-actions-demo --public --source=. --push

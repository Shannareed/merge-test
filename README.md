echo "# merge-test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git remote add origin https://github.com/Shannareed/merge-test.git
curl -sS https://webi.sh/gh | sh
gh auth login
git push -u origin main
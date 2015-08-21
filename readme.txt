ls
git config --global user.name "ajay"
git config --global user.email "ajay@test.com"
git init myproject
cd myproject
ls
git status
git add .
git commit -m "changed"
git log
git status
git diff
git add .
git diff --cached
git commit -m "changed2"
git log
to exit log editer hold Shift + zz
git log --oneline
git commit -a -m "shortcut"
git status -s
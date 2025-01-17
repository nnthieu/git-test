cd git_test
git init git-test
git remote add origin https://github.com/nnthieu/git-test.git
git add git-test.py
git commit -m "Add git-test.py"
git remote set-url origin https://<my_token>@github.com/nnthieu/git-test.git
git push -u origin main

Git is a  distributed version control system.
Git is a free software under the GPL.
Git has a mutable index called stage.
Git tracks  changes.
Github use git to handle code,more safty.

git init
cd .git
cd ../
git add readme.txt
git commit -m "wrote a readme file"
git status
git diff readme.txt
git add readme.txt
git commit -m "append GPL"
git log
git log --pretty=oneline
git reset --hard HEAD^
git reset --hard f0e09
git reflog
git checkout -- readne.txt
git reset HEAD readme.txt
git rm test.txt
git remote add origin http://github.com/llinniee/-.git
git push -u origin master


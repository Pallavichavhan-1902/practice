# practice
git version
git config --global user.name
git config --global user.email
git init myrepo
cd myrepo
touch sample.txt
git add sample.txt
git add .
git status
git commit -m "first change"
git log
git branch "branch1"
git checkout "branch1"
touch newfile.txt
git add .
git commit -m "second change"
git status
git checkout master
git merge branch1

github 
login
create new repo
copy url
git clone <url>
cd <reponame>
(cd repo1)
git status
(check the file manager and check msg into readme.md
git status
git add .
git commit -m "change 3 done"
git btanch branch2
git checkout branch2
git push origin <branch-name>
goto github
right click-> setting -> developers setting -> personal access token -> token classic -> generate new token classic-> click checkbox(except workflow)-> generate token-> go to terminal
git remote set-url origin http: paste token id @github.com/paste(username/reponame)
git push origin<branch-name>

goto github
github->pull request option-> new pull request-> compare-> <branch-name>->create pull request-> merge pull request-> confirm merge
git status
if we want to make changes on main branch the add some content on README.md file & save it.
git checkout main
git add.
git commit -m " change done"
git pushh origin main
git fetch origin main
git pull origin main
git add.
git commit -m "change done"
git push origin main




gitlab

gitlab -> account create-> create project-> open gitlab-> create a new project on gitlab->
add some content in it->copy project url -> goto terminal

git clone <gitlab_project_url>
cd smaple
ls
git branch branch1
git checkout branch1
ls
touch demo.txt
ls
git checkout master
ls
git checkout branch1
git add .
git commit -m "first commit"
ls
git checkout master
ls
git pull origin master
ls













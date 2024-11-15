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

bitbucket
goto bitbucket -> login-> create repo-> click on clone(copy url) -> paste the url> on terminal > password
 how to create password
 setting > personal bitbucket setting > app password > create app password > copy id > paste on terminal
 goto terminal > paste the url
 cd demo
 touch sample.txt(add some content in file)
 git add .
 git commit -m "first commit"
 git status
 ls

 git branch branch1
 git checkout branch1
 git status 
 ls
 touch sample2.txt
 git add .
 git commit -m "second commit"
 git status
 ls
 git push origin branch1
 git pull origin main




 jenkins



 terminal
 sudo systemctl status jenkins

 new terminal

 ngrok http 8080
 here we see the status of ngrok > from that click on a forwarding link and open a link on browser or copy the link upto free.app and paste it on a browser and open it


 click on visit site
 usename -> kkwagh
 password -> srv001

 github

 login on a github(on new window) > open the repo thaete we want to build on a jenkins > copu the repo/ project link from code(https)

 jenkins

 click on new item > enter item name(eg.demo) > select freestyle project > click ok > form source code management > select git > paste the git repo Url(that copied from github) > from branches to build( write main istead of master) > from build (write main istread of master) > from build triggers slect github hook trigger for GITScm polling ->
 click aply save


 github

 on repo -> click setting-> webboks > add webbook > on payload URL(copy thr url form jenkins or terminal upto free.app and paste here) (on this url add a github-webhook/ after free.app) > select content type (application/json) > select send me everything > click add webbok > then refresh(see green tick) > click on build now(after sucessful build) => click workspace and run the html file > optional > (found error)

 click config > build steps > select execute shell > write command > cp -r */var/www/html/ > apply & save > click build Now
 0.0.0.0
















 













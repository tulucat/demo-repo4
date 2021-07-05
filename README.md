# demo-repo4
hi

#clone files from github, push to main

git clone git@github.com:tulucat/demo-repo4.git
    clone from github

git status
    displays modified files, not saved in a comit

git add . // git add index.html
    stage files on git

git commit -m "message" -m "description"
    saves files on git

git push origin main
    push to github on origin path(root), main branch

#create new repo from local machine

git init
    initialize, add .git folder

git remote add origin git@github.com:tulucat/demo-repo5.git
    add new repo as origin

git remote -v
    shows remote url
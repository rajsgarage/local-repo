#Pushing a Local Repo to github
this was created on local machine first




LOCAL REPO pushed to REMOTE
create folder, create some file.
$ git init
$ git status
$ git add .
$ git status
$ git commit -m ""
$ git push origin master
but origin not defined, git doesnt know where to push
create empty repo on github and then link it here
$ git remote add origin https://github.com/rajsgarage/local-repo.git

$ git remote -v
origin  https://github.com/rajsgarage/local-repo.git (fetch)
origin  https://github.com/rajsgarage/local-repo.git (push)
--shows if any remote directories currently connected to

$ git push -u origin master
instead of using "origin master" everytime you set upstream

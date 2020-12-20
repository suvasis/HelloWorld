# HelloWorld
# stormclone

#git getting started

https://www.google.com/search?client=safari&sxsrf=ALeKk022aNLr7L_mVcrvPqVZjtwiBm2eVA%3A1608434451288&source=hp&ei=E8PeX5P_DsTY-gTY95LYCw&q=git+tutorial+command+line&oq=git+t&gs_lcp=CgZwc3ktYWIQAxgCMgcIABDJAxBDMggIABCxAxCRAjIECAAQQzIECAAQQzIECAAQQzIHCAAQsQMQQzIECAAQQzIECAAQQzIECAAQQzICCAA6BAgjECc6BwgjEMkDECc6BAguECc6BwgAEBQQhwI6CggAELEDEBQQhwI6BQgAELEDUKsNWJodYIVRaABwAHgAgAFeiAG0A5IBATWYAQCgAQGqAQdnd3Mtd2l6&sclient=psy-ab#kpvalbx=_HcPeX-HGN4G6-gTHm77AAQ15

basic commands:

#first time setup

#set config values: - add name and email

git config --global user.name "suvasis mukherjee"

git config --global user.email "suvasis@yahoo.com"

git config --list

#initialize a repo from existing code
git init --- run this command from within the directory

             .git contains everything inside to track everything inside

#before first commit

git status

#to ignore files

touch .gitignore

add the files or extensions you want to be ignored..

#you can check

git status


#push changes to the remote

git diff -- see changes

git status

git add -A -- to staging

git commit -m "message" -- committed locally

git pull origin master -- pull from the repo

git push origin master --- master is the branch and origin is the remote repo

#common workflow to workw with git

git branch <name of branch>

git branch  --- list all the branches

git checkout  <branch>

git branch


# merge a merge
git status

git add -A  ---to staging

git commit -m  "mgs" -- committed to local repo

git push -u origin <branch>

git branch -a  -- shows bothe the local and the remote directories


git checkout master

git pull origin master

get branch ---merged -- merged branches

git merge <branch>


working dir -> staging area --> .git directory repository
               to be committed -> commitwd

# add files to staging area

git add -A

#to remove from staging

git reset <file name> or git reset --- to remove everything

git ststus

# to commit

git commit -m "how to use git"

git status -- nothing to commit 

git log

# clone a remote repo

git clone <url > <where to clone>

git clone github.com/suvasis .

# view info ab the remote repo

git remove -v --- list the info ab the remote repo

git branch -a -- all the branches

#mwerge a branch

git checkout master

git put origin master

git branch --merged

git merge <branch name>

git push origin master 


# to delete

git branch --merged

git branch -d <branch name>

git branch -a

git push origin --delete <branch name>

git branch -a







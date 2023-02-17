# git
Git and Github repo


git clone                    ==> clone the repo to my local machine
<br>
git status                   ==> to check for the unstaged updates for files and folders 
<br>
git add                      ==> stage files to add them to local repo
<br>
git commit                   ==> commit the staged files 
<br>
git branch                   ==> to know my local branches 
<br>
git remote -v                ==> to know the name of remote repo
<br>
git push                     ==> push the changes from local repo to remote
<br>
git pull                     ==> pull and merge from remote to local repo
<br>
git config --list	           ==> to get the list of git configrations
<br>
git config --global --edit   ==> edit configrations from editor
<br>
git init                     ==> to start and create git file
<br>
git remote add origin <ssh>  ==> to add remote repo to my local repo
<br>
git branch                   ==> to see all branches
<br>
git branch <anyname>         ==> to create a branch with name
<br>
git checkout <exist branch>  ==> to go to spicified branch
<br>
git branch -d <branchNme>    ==> delete spicified branch
<br>
git checkout -b <branchNme>  ==> create a branch and go to it direct
<br>
git branch -m <newName>      ==> rename current branch
<br>
git merge <branchName>       ==> merge the selected branch with the spicified branch
<br>



---

## Explane :

git add <unStaged file name 1> <unStaged file name 2> ..etc

or to add all we can say

git add .


after doing add all files on staging area and ready to commit on local repo

if i want to delete any file from stage area we use :

git reset head <file name>

or to reset all we can say

git reset .


now we have the staged files and every thing is ok we need to add them to local repo by 

git commit -m 'here we write any message to descripe the commit'

affter commit the changes we can do push now by :

git push <remoteName> <localBranchName> 

remember: can get remote name by ( git remote -v )

eg: git push origin main

---
## Explane :

if i want to get updates from remote repo we use :

git pull <remoteName> <branchName>

git pull origin main

---
## Explane :

if i want to show configration we use :

git config --list  to show all config list 

if i want to get a spicific thing i can use 

git config --global <any config name>

eg : git config --global user.email 

if i want to set this config 

git config --global user.email 'enter any email here and it will be editied'
 

---
## Explane :

How to create repo on local then addit to remote :

- create repo folder 
- inide this folder we do ( git init )
- git remote add origin < ssh or https link from github eg: git@github.com:Alhaimouni/test.git >
- git push -u origin main "this step do pull remote main then push my main to remote repo"

---
## Explane :

merge local branch with local main 

select main branch and then we do :

git merge <branchName>

---

# demo 2 


Demo repository

# what if we create repository local,

$ git push origin main
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

# brcause git doesnt know about any main branch


# we have to create a connection

# 1: Create Empty Git repository on github 
   1.i:  create and copy link
   1.ii:  git remote add origin (link)  -> remote means somewhere else but not on this computer
   1.iii: git remote -v  -> to check newly added repos
   1.iv: git push -u origin main  -> -u means Upstream
# demo-reposits2


# branching: Every branch will have same repository but different data in it, 

# then push 
# will give another command


# PR or  Pull Request

pulling Request to pull data/code to another branch

making pull requesst from main branch to new branch

# Steps:
1.Link given after pushing code to new Branch.

2.Using Github

Use : when somebody addedd code to new branch you inspect it and then merge it with your main branch
i.Open Pull Request section on github from <>code
ii.Enter Name, Enter Desc
iii.You can add comment on code of lines
iv. Merge Pull Request


after this code on vs code wont change becuse we used github
to change code on vs code main branch also, we have to import/update it

v. Git pull origin main
or
git pull
only if upstream is on

then Delete other new branch because now we dont need that.

git branch -d newbranchname

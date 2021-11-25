
### git clone <url>
### git remote remove origin
### git remote add origin <url>
### git pull origin main[may vary]


### see all branches(also show which branch you are currently on):
> git branch
### construct new branch: 
> git branch <newBranchName>
### switch to other branch:
> git chechout -b <BranchName>

## get other committed version:
### use: **git log --oneline**
### say you have the following output
> 6befdf4 (HEAD, origin/main, origin/HEAD, main) add branches comment
c1c0158 new README
26f53c0 nov22
fdca597 table-card update
eb41f3a fourth commit, add package.json
d60df23 third commit
946c722 second commit
e7b4f86 add index.html
### and you want to go back to version with commit 'nov22', then use:
### git checkout 26f53c0
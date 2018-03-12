GIT has 2 repositories which is on local and remote. Use origin to reach access in remote repository.



#Pull (Get all commit history and files from remote repository to local repository)

`git pull origin 'namebranch'`

#Rebase (merging file and commit between two branch from current branch from target branch on Local repository)

`git rebase 'origin/namebranch'`

#Fetch (get commit history from remote repository to local repository)

`git fetch origin 'namebranch'`
`git fetch origin` -> update all history commits from remote branches

#Merge (merging file from remote repository to local repository)

`git merge remotename/branchname`

#Delete branch remote repository
`git push origin --delete feature/login`


###note
remote repository = git repository


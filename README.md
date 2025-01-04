Lab 2 ● Write in the README.md file, how to remove the branches locally and remotely.

ensure first that you are not exist in this branch --> go to main (git chechout main) 


    ---- Removing Branches from the local repo :
        git branch -d branchName

        -- If the branch has not been merged we also write(force):
        git branch -D branchName


    ---- Removing Branches from the remote repo
        git push origin --delete branchName

-----------------------------------------------------------------------------

Annotated tags vs Lightweight Tags 

| **Tag Type**       | **Description**                                                                                   |
|--------------------|---------------------------------------------------------------------------------------------------|
| **Annotated Tags** | Store additional metadata such as the tagger's name, email, date, and a message.                  |
|                    | Stored as full objects in the Git database.                                                       |
|                    | Ideal for release versions where detailed information is needed.                                  |
|                    | Created using `git tag -a v1.0 -m "version 1.0"`.                                                 |
| **Lightweight Tags** | Just pointers to a specific commit without additional metadata.                                  |
|                    | Not stored as full objects in the Git database.                                                   |
|                    | Suitable for temporary or private tags where detailed information is not necessary.               |
|                    | Created using `git tag v1 0`.                                                                     |





-------------------------------------------------------------------------------
task steps :

create branch and enter: git checkout -b dev = git branch dev && git checkout dev

to add changes to the local repo: git add . git commit -m " "

to push changes to the remote repo: first time: git push -u origin [branchName] other times: git push

to merge branch with main go to main : git chechout main merge : git merge [branchName] push to remote repo : git push
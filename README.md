Lab  2 
 ● Write in the README.md file, how to remove the branches locally and 
remotely.


first : 
create branch and enter:
git checkout -b dev   = git branch dev && git checkout dev

to add changes to the local repo:
git add .
git commit -m " "

to push changes to the remote repo:
first time:
git push -u origin [branchName]
other times:
git push


to merge branch with main 
go to main : git chechout main
merge : git merge [branchName]
push to remote repo : 
git push
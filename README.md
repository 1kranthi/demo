Starting of the git hub turorial

# To know the differnce files in braches 
git diff branchName

# To reduce lines
if the files is exist already then to commit and add
git commit -am "message"

# To create a new branch
git checkout -b feature(name as descriptive as possible) and enter 
Result: you will be redirected to that perticular branch

# To navigate to main again
git checkout main
by this command you can navigate between branches

# To push the code in feature branch to git hub
enter git push command if this shows an error saing has no upstream then enter this command
git push -u origin feature 
then a new branch is created and now you can raise a PR (Pull Request)

# Managing and merging branches and sending a Pull Request
click on compare and pull request
Add the desciption of changes into the ddescription  and create a pull request by clicking create pull request 
in te commits you can see that changes for the pull request 
Click on murge pull request then the branches will be merged    

# After completing the merge
delete the feature branch after the merge
git branch -d feature(branch name)

# Repeat
Repeat this for as many time as required

# If having a merge conflit
creating a merge conflit and resolving it
merge conflict happen when two different branches are pushing into the same method or file resulting conflit 

## Solving in code editor 
remove warnings which git provided or click on incomming change or current chnage then commit thus the merge conflit is resolved

## Undoing commits/stages in git
to reset the staged file 
git reset README.md(file name)
it will reset onestep back from staging to modified

To Completly undoing the commit and going one step before even after the commiting 
git reset HEAD~1
then it is will go back to modified

## To check all the commits in the branch
git log
the commit will be arranged in reverse cronologgical order 
What command do you use to setup a git repository inside of your folder?
    git init
What command do you use to ask git to start tracking a file?
    git add -A
What command do you use to ask git to move your file from the staging area to the repository?
    git commit -m "enter message here"

What command do you use to pull any changes from the master repository into your local repository?
    git pull upstream master
What command do you use to unstage a file?
    git reset -- <filename>
What command do you use to change your files back to how they were after a commit?
    git checkout -- file.name
Why is it important to use -- when changing files back to a previous state?
    The double dash is used in git checkout to revert or discard changes. Or else in would change branches.
Why might you want to reset your files back to a previous commit?
    In case you wanted to revert back to the state of the file before the commit.

What command do you use to create a branch?
    git checkout -b branchName
What command do you use to use a different branch?
    git checkout branchName
Why would you want to use a branch other than the default master?
    If you wanted to test a chunk of code for functionality without affecting the master.

Give an example for when you would use git merge and give an example for when it would be better to submit a pull request to have your branch merged
    You would use a git merge when you want the changes on the branches you have been working on to reflect on the origin master.
    You would submit a pull request to have your branch merged when multiple people may be working on the same file and you would be able to collaborate with them with the changes made.

What command do you use to send all of the work that you've done locally to your remote repository?
    git push -u origin name
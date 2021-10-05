git clone <repo_link>   ==> Create a local copy of your repo

cd <repo_name>

git checkout -b <name_of_the_branch>  ==> Create a New branch and switch to that branch

<adding new codes as required>

for staging the updates to the code

git add * (or) git add .   ==> Stage all the updated files
git add <file_name>        ==> Stages only the specified file

To restore any of the staged files

git restore --staged <file_name> 

git status   ==> Check Status of your code

git branch   ==> Check the current branch you are working with

git commit -m "Adding directly to main branch" ==> commit the changes (commit id)

git pull

git push  ==> Make changes to your remote repo

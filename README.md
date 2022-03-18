# zemoso-training

STEP 1. Create a local git repository using the following commands

mkdir firsT-git-repo
cd first-git-repo
git init - it will place a .git file in the project

STEP 2. Create a text file named hello_world and copy the text provided

STEP 3. FIRST COMMIT

git add hello_world
git commit -m "Initial Commit"
git remote add origin url
git push origin main

STEP 4. to interchange string in text file. 
sed -i 's/ to / name /g' hello_world

git diff to see the differences in files

Commit the changes and push it to git using:

git commit -m 'another commits'

STEP 5. to revert back all the changes to the text file.
git revert HEAD 

Create a new_branch with name new_branch.
using git checkout -b <branch name>
By using the following command replace all "Torvalds" words with name

sed -i 's/Torvlds/name/g' hello_world

Commit the changes and push it to git using:

git commit -m "First Commit in new_branch" 
git push origin new_branch
Merge new_branch to the previous branch.

Step 6.By using checkout command we can switch to the master branch and merge both the branches by using following commands

 git checkout
 git merge new_branch
Clone the repository from the Git to local repository in some folder

STEP 7. By creating a new directory git_clone_repo and initializing git in this folder,clone the git repository

 mkdir git_clone_repo
 cd git_clone_repo
 git init
 git clone url

 to get a repository from github :
git clone https://github.com/AbFeraly/Test2.git

(using cd to access a folder cd /Downloads/subFolder/folder2/    ; if inside home
if not use ~ in the begining)

(ls : lists what inside the folder u are in)

git add : used to add untracked files 

git add -A ; to add all files      /what does it mean with adding untracked files
or git add file.ext

then we make a commit after adding

git commit -m "whatever is changed"  //what is m ,git diff example

UPDATING REPO:	

This should work for every default repo:

git pull origin master

If your default branch is different than master, you will need to specify the branch name:

git pull origin my_default_branch_name
______________________


    git fetch is the command that says "bring my local copy of the remote repository up to date."

    git pull says "bring the changes in the remote repository where I keep my own code."

Normally "git pull" does this by doing a "git fetch" to bring the local copy of the remote repository up to date, and then merging the changes into your own code repository and possibly your working copy.

example :

    Update your local repo from the remote (but don't merge):

    git fetch

    After downloading the updates, let's see the differences:

    git diff master origin/master

    If you're happy with those updates, then merge:

    git pull






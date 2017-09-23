A sandbox project for experimenting with Git.

Key commands
=============
Make a new directory
mkdir ~/<DirectoryName>

Navigate to directory
cd ~/<DirectoryName>

Initialize Local Git Repository
git init

Git Status
git status
git status -s

Create a text file
touch <FileName>

Add a file to the next commit
git add <FileName>
git add .

Commit a file
git commit -m <Message>

Connect a local repository with a remote repository
git remote add origin <RemoteURL>

Get a list of all the remote origins known by the local repository
git remote -v

Push files to remote
git push --set-upstream origin master
git push

List files changed but not yet staged
git diff

List files staged to go into the next commit
git diff --staged
NB: press q to return to the command line


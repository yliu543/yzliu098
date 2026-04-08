# My First Repo:
## Terminal Steps for Creating and connecting a Repository:
3. Create the online repo to connect with. Go to github.com --> click new repo
4. Give it a name and hit 'Create Repository'
5. Copy 'git remote add origin' command and paste in vsc terminal and hit enter
   - this command links your local repo to the remote destination
   - check this by running the command 'git remote -v' shows a remote destination if you have one

## Steps to make and commit a new version of your project:
1. 'git add .' - add all files in this directory to a new project version.
   - **This does not commit, it just stages changes, these changes can still be over written**
2. 'git commit -m "commit message"' - this command makes a commit and gives it a message

## Steps to PUSH commits to github.com:
1. 'git push origin -u main' - pushes all commits to github
2. all subsequent pushes 'git push'

## Vocab:
- 'commit' - to save a version, you can commit locally, push commit to git hub.
- 'push' - to push commits to online repository
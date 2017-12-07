========== 3 states with Git ==========
(1) Working directory
    --> Area where all of our files and directories and changes are living all the time
(2) Staging area ("Double check area")
    --> Files in directories that we explicitly add to the staging area
(3) Repository (.git)
    --> Where all our snapshots are stored

========== Steps to use git ==========   
Step 1: Git init
        --> Done using [git init]
        --> Check using ls-a
        --> (master) = Git is initiated
Step 2: Git add
        --> Done using [git add <file>]
        --> Check using [git status]
        --> Add files to staging area
Step 3: Git commit
        --> Done using [git commit -m "Message here"]
            --> -m is a flag
            --> present tense verb + short description
        --> Check using [git log]
        
========== Adding same file types ==========
Wildcard --> Asterisk (*.<fileextension>)


========== Adding all files ==========
git add -A --> Adds all files and folders from the directory that you're in

========== Removing files from staging area ==========
git reset HEAD <file>
git rm --cached <file>

========== Ignoring files ==========
Step 1: Create a file named ".gitignore"
Step 2: Add file name into the .gitignore file

========== Branching ==========
(1) git branch 
    --> List the branches we have
    --> * shows which branch you are at
(2) git checkout -b <branch_name>
    --> Create a new branch
(3) git checkout <branch_name> 
    --> Switch to another branch 
(4) git merge <branch_name>
    --> Merge the branch specified to the current branch you are on
(5) git branch -d <branch_name>
    --> Remove a branch (Not recommended)

========== Linking repositories to GitHub account ==========
Step 1: Create new repository in Github
Step 2: Obtain SSH keys from C9 account
Step 3: Paste SSH keys in Github (Settings --> SSH and GPG keys --> New SSH key)
Step 4: Link repository in c9 to the repository in GitHub
        --> git remote add origin <url>
            --> Add a short name "origin"
        --> git remote -v 
            --> Check that origin is added as a remote
        --> git push -u origin master
            --> Push the commits in the local branch named master to the remote named origin
            --> Local branch master is now on a remote branch also called Master on GitHu, and the remote is called origin
            
            



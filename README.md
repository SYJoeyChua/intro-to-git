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
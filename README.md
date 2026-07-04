
<process from git to local machine>
git clone <link> #copy from git to local machine
git status       #display hte state of code
            #file may be Untracked modified staged and unmodified
            # git add "file name .exe" untracked to modified
            # git add . add all files  
            # git commit -m "message"  modified to unmodified
git push origin main  
            # push upload changes local system to remote or git


<process from local machine to git>
mkdir <file name>   # to create new file
Ls -Force           # to check git repo in file
git init            #initialize empty git repository
                    #create repo in git
git remote add origin <git link of repo>
                    #git repo ko local machine say link krnay k liye
git remote -v       # to verify remote access
git branch          # to check branch
git branch -M main  # to rename branch name
git push origin main
                    #git per code push krnay k liye

<Git Branch>
git branch          # to check branch
git branch -M main  # to rename branch name
git checkout <branch name>        
                    # to navigate between branches
git checkout -b <-new branch name->
                    #for new branch creation
git branch -d <-branch name->
                    # for delete branch
<Merging code>
1St method
git diff <-branch name->
                    #to compare commit, branches, file and more
git merge <-branchname->
                    #to merge two branches
@nd Method
PR pull request

<undoing changes>
git reset <-file name->
                    # staged change
git reset HEAD~1    # commited change
git reset <-commit hash->
                    # commit changes for many chnges
git reset --hard <-commit hash->

git log             # to check all commits
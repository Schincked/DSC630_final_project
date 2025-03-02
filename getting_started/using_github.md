## Github Cheat Sheet
1. Adding files to git stage
    - `git add file_to_add.py` 
2. Adding all files to git stage
    - `git add .`
3. Committing all staged files
    - `git commit -m "This is my commit message. I will put the changes I made here`"
4. Create new branch
    - `git branch my_branch`
5. Switch to branch
    - `git switch my_branch`
6. Create and switch to new branch in one command (combines 4+5 together)
    - `git switch -c my_branch`
4. Pushing all commits from local branch to the remote branch
    - `git push origin my_branch`
5. Pulling changes from remote branch to local branch
    - `git pull origin my_branch`
# learning_repo
Summary: Learning and testing the GitHub repository

## Creating a repo
   - Save a ".md" file as the text overview of the project or plan of the project

## Terminal
- "q" to get out of locked situation
   - * "clear" to clean the terminal
   - 1. "git clone (HTTPS)" to clone the project to your computer
   - 2. "cd (file name)" to jump into the file
   - 3. "ls -la" to uncover hiden files and documents
   - 4. "git status" to see the changes
   - 5. "git add ./(file name)" to track the file
   - 6. "git commit -m "(massage)" -m "masssage" ..." to commit the changes localy
   - 7. "git push" to push the new files and changes to GitHub

## Branch
- Main is thhe main or master branch
- Stared and highlighted branch is the branch you are on
   - 1. "git branch" shows the branch numbers you have
   - 2. "git checkout -b (name)" allows you to create a new branch 
   - 3. "git checkout (branch name)" switch to the branch
   - 4. "git push -u origin (branch name)" to create a Pull Request (PR) in GitHub
   - 5. "git diff (branch name)" shows the differences between the branch and main
   - 6. "git pull" to get the file from GitHub
   - 7. "git branch -d (branch name)" to delete the branch    
- "git commit -am "massage" " for modified files
* Merrge conflect happened in developmen

## Other Commands
   - 1. "git reset" will undo the last step
   - 2. "git reset HEAD~1" will undo the latest commit
   - 3. "git log" shows all the past commit
   - 4. "git reset --hard (commit log code)" to reset to a certain point
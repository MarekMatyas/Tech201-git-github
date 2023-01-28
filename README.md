# Tech201-git-github
## Git practice notes

1. Create a repository on GitHub + README.md file
2. Open GitBash
3. To create a new folder (directory) `mkdir` + name of the directory you want to create
4. To navigate to the folder you have just created use `cd` command (change directory) + the name of said directory
5. `pwd` shows the current location
6. `git clone` + HTTPS URL from GitHub creates a link between the local and global 
7. `ls` to list directories 
8. `cd` + the name of wanted directory
9. `pwd` to double-check the current folder location
10. `ls` to list directory because we are now inside the folder we just created (README.md should be displayed)
11. `nano README.md` allows to edit the README.md file
12. `ctrl+x` to save the changes, Y for yes and N for no and lastly hit Enter to confirm
13. `cat` + the name of the file (README.md) display the changes rather than going with `nano` command
14. `git add .`  to add all the changes
15. `git status` shows us the status of the README.md file that has been modified
16. `git commit -m "message about the change"` means we are saving the changes
17. `git push -u origin main` (main meaning the branch name) to send the changes from local to global




## Side note

### If encountering a merging problem that is because the changes differ from local to global
Please follow these steps to resolve:
1. `ls`  to display the list of directories 
2. `ls -a` (all) shows us the hidden folders (.git folder) this *.git* folder saves all the information like *status* and *commits*
3. `rm -rf .git` to remove
4. `ls -a` to list all folders and make sure that *.git* folder has been removed 
5. Then copy the *HTTPS* from GitHub and use `git clone` + URL from GitHub repository to clone again
6. `cd` + name of the folder (example Tech201-git-github) to navigate to the correct folder
7. `nano README.md` to open the editor to add and test the functionality 
8. `cat README.md` displays all the changes made 
9. `git status` to check if the changes were added to commit, if not then follow the next steps
10. `git add .` to add all the changes
11. `git status` to check if all the changes are ready to be committed 
12. `git commit -m "relevant message"` to commit the changes 
13. `git push -u origin main` to send the changes to global

### Now we should be all up and running 

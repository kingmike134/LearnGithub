# Github Vocab

Repository - A project containing all of your coding files and folders.

Pull - A way to grab files from github and put them on your local machine.

Git Add - Tells git to track (in other words pre-SAVE) a new file that you created or pre-save an existing file that you edited. Can quickly do this by doing "git add ." in the terminal. Using the period pre-saves all the files that you either created or edited. If you want to do an individual file just put the individual file name after the "add".

Git Commit - This actually saves the file on git and saves the changes made. It will save these changes and leave a history of all saves, or commits. Think of commit as github's way of saying save. Do this by typing "git commit -m "Type Title of change" -m "Type optional description of change" ". Now this saves the files only locally.

Git Push - Makes the commit live on github repository online. Just type "git push" in command line.

Pull Request (PR) - A request to have your code pulled into another branch. Once a PR has been made anyone can view the code, comment on it, or ask to make changes/updates. Once you've made a PR you can still update the code and make additional commits and push them up to github as long as its on the same branch you're making the PR with. Once the PR is merged with the master branch you'll delete the source branch and then if you want to make additional updates or features/fixes then you'll just make another branch, and repeat.

## Subheader - Hidden Files

When accesing the repository you pulled on your local machine or device, there is hidden folders that show your changes throughout. It ends with a ".git" and will track all the saves you made. To see these hidden folders just list all hidden directorys by typing "ls -la" in the terminal. Make sure you are using bash shell as well. 

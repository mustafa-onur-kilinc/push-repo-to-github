# Demo Repository-2

I am using this Git repository to practice pushing a locally created repository to GitHub.

## Steps to Push a Local Repository to a GitHub Repository

1. Create a directory/folder in your computer.
2. Open your terminal and go to the directory/folder you have created in step 1.
3. Enter "git init" command at terminal and press Enter to turn your directory/folder to a local Git repository.
4. Create a new, empty repository in GitHub.
5. Copy the empty repository's SSH link.
6. Go to the terminal page, enter "git remote add origin" command, add GitHub repository's SSH link you have copied in step 5 and press Enter.
7. Type "git remote -v" command to the terminal page and press Enter to check if the local Git repository and the empty Git repository in GitHub are connected.
8. Make whatever changes you want to make in your local repository.
9. Write "git status" command to the terminal page and press Enter to check which files should be staged for commit.
10. Enter "git add [filename] [filename] [...]" or "git add ." command to the terminal page to stage which files will have their changes committed to Git.
11. Type "git commit -m [your description title] -m [your extra description]" command to the terminal page and press Enter to commit the changes you have made and staged to your computer.
12. Enter "git push origin [branch name]" (if no branch has been defined in GitHub repository, you can write master for branch name) command to the terminal page to push your committed changes in your local repository to your GitHub repository.
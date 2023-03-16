# Demo Repository-2

I am using this Git repository to practice pushing a locally created repository to GitHub and branching.

## Steps to Push a Local Repository to a GitHub Repository

1. Create a directory/folder in your computer.
2. Open your terminal and go to the directory/folder you have created in step 1.
3. Enter "git init" command to the terminal to turn your directory/folder to a local Git repository.
4. Create a new, empty repository in GitHub.
5. Copy the empty repository's SSH link.
6. Go to the terminal page, enter "git remote add origin" command, add GitHub repository's SSH link you have copied in step 5 and press Enter.
7. Type "git remote -v" command to the terminal page and press Enter to check if the local Git repository and the empty Git repository in GitHub are connected.
8. Make whatever changes you want to make in your local repository.
9. Write "git status" command to the terminal page and press Enter to check which files should be staged for commit.
10. Enter "git add [filename] [filename] [...]" or "git add ." command to the terminal page to stage which files will have their changes committed to Git.
11. Type "git commit -m [your description title] -m [your extra description]" command to the terminal page and press Enter to commit the changes you have made and staged to your computer.
12. Enter "git push origin [branch name]" (if no branch has been defined in GitHub repository, you can write master for branch name) command to the terminal page to push your committed changes in your local repository to your GitHub repository.

## Steps to Create a New Branch in a GitHub Repository

1. Open your terminal and go to the local repository you want to create branches in.
2. Type "git branch" command to the terminal page and press Enter to check if the branch you want to create has been created already. If the branch you want is not listed, go to step 3. Else, go to step 5.
3. Enter "git checkout -b [new branch name]" command at terminal to create a new branch named [new branch name].
4. Type "git branch" command to the terminal page and press Enter to check if the new branch has been created successfully.
5. Write "git checkout [branch name]" command at terminal to go to the branch named [branch name].

## Steps to Pull a Branch

1. Stage the changes you have made using "git add [file to stage]" command.
2. Commit your changes using "git commit -m "[your description]" -m "[your detailed extra description]"" command.
3. If you want to locally merge your branch to your main branch, go to step 4. If you want to push your branch to GitHub and merge your branch to main branch there, go to step 5.
4. Switch to main branch using "git checkout main" command and enter "git merge [branch to be merged]" command to merge the branch to main branch locally.
5. Enter "git push origin [branch name]" command to the terminal to push your local branch to a GitHub branch of the same name.
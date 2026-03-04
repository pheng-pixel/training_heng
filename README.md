# TRAINING_HENG

tHIS IS MY INTERACTIVE README

## How to Create a Git Repository from an existing project

1. Initialize training_{USERNAME} as a Git repository by running usethis::use_git() in the Console. Choose yes when asked if it’s okay to commit any uncommitted files. Choose yes again if asked to restart R. Once complete, you should see the Git tab appear in your top left pane in RStudio and a .gitignore file appear in your Files tab.

2. Create an upstream remote repository on GitHub by running usethis::use_github() in the Console. Your web browser should open up to your new GitHub repository, with the same name as your local Git repo/R Project.

3. Ensure that your default branch is named main rather than master by:

    running git branch in the Terminal to list all your branches (you should currently only have one, which is your default)
    if it’s named master, run the following line in the Console to update it usethis::git_default_branch_rename(from = "master", to = "main")

You’re now ready to edit, stage/add, commit, and push files to GitHub as practiced earlier!
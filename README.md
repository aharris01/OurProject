# OurProject
# Partner 1: Dominique Deveaux
# Partner 2: Aidan Harrison
## Working with Remotes
1. When working with a remote repository, you don't directly change it when working locally.
2. The common repository gets updated by users updating their own local copies of the repository and pushing it to the common one.
When you need to update your local repository you pull from the common repository.
3. From the common repository everyone can view the commits that other users have made and pushed
4. While working on your local repository it may not be possible to push your changes because someone else has pushed some
changes of their own that conflict with your changes, so you will have to pull their changes and fix any conflicts within that.
5.	The git pull command is essentially two commands, fetch and merge, combined.
## Working Locally
### Important concepts I have learned about working locally with git
1. "**git status**" can be used to see the active branch, if it's updated, and if there's anything to commit.
2. git can be used to keep track of **file versions**, and does not have to be used in conjuction with a remote repository.
3. **Branches** can be made using "git branch <branch name>".
4. The workflow for working locally consists of transfering fields between the **workspace, staging, and local repository**.
5. The staging and local repository are **virtual "places" git creates and tracks**. They are not normal directories like the workspace.

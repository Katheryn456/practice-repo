# practice-repo

git clone (paste HTTPS/SSH from GitHub from big green button Code)

Open directory in VS Code

Everyone will work on separate branches, not on Main.

Someone else will review code before merging your changes (Second pair of eyes)

Invite Collaborators (to add teammates). Teammate must accept invite via email.

Ask Robert/Lazaro re: git commit with changes to new branch. Currently, git status of the new branch doesn't show any changes/is empty. Evan might know this as well.

Maybe have Evan be the person to create the repo, where everyone else will be a Collaborator. Robert mentioned: we'll fork it later, so that the person's name is not the only one on it.

create project in GitHub

create GitHub issue "set up file structure"

git status
git add .
git commit -m  // COMMIT BEFORE YOU PULL. Else, it'll erase
git pull origin main // git pull (if not on Main, then you'll need to do git pull origin main) to make sure no new changes that might conflict with the branch, before pushing.
git push origin setUp // Push to the repo. git push origin [local branch name]

complete git pull in GitHub pull request tab. Assign reviewer and project.

To download teammate's branch for review:
git fetch
git checkout -b [branch name of teammate] origin/[branch name of teammate]

how to update if another branch merge before yours
git commit // commit current changes before pulling
git pull origin main
resolve conflict
git add .
git commit

git pull origin main // just in case
git push origin [branchName]

GitHub cheat sheet from Mouhamed: https://training.github.com/downloads/github-git-cheat-sheet/

From Robert: https://github.com/reanderson89/practice-repo 
# fortnite-nerdz


## Git Flow

Getting Started:

1. Clone the repo
2. Create a branch using:

> `git checkout -b [name]/[name-of-feature]`

3. Develop within the branch
  - Make sure to commit (save) your work often using:

> `git commit -m "[description-of-work]"`

4. When feature is completed, commit your work, then rebase by using the following"

> `git rebase [completed-branch-name] develop`

5. Submit a Pull Request to the `develop` branch
6. Request review from other devs.


You can type `git status` to see what files have been changed and staged for commit.

You stage files for commit by typing `git add [path to file]`. (You can see the paths from `git status`).

Once you have staged your files, you can commit them by typing `git commit`.

Once your branch is ready, push it to GitHub by typing `git push origin [name-of-branch]`. Then you can make a PR.

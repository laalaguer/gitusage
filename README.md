# gitusage
Discuss the Git usage on local and on remote

## Three different Areas

Working Directory: A place where you store your code, make changes.

Staging: A hidden place where you comitted your changes.

Repository: A Place where all your code, history versions are stored.

## Git Commands:

`git add your-file-name` Add your file to git tracking, so later you can commit them as real changes. But if you `add`, then mofidy the file again, you need to run `add` again, as the file is modified again.

`git commit -m "hello, my first commit"` Commit your changes to staging area where you really want those changes.

`git status` check the current status of your git repository.

`git diff HEAD~1` A useful command, to tell difference between your current working directory and the very last commit of your working tree.

`git reset` will make your commited files, back to unstaged status.

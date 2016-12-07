In git, commits are the saved changes.

Commit is a record of what files you have changed.

Staging environment (index) is the state of the branch just before a commit, after the git add command. The command git add, i.e. adding to a stage, means adding for the next commit  .

Anything committed can be recovered any time. But loss of any file or change that you did not commit is a permanent loss. e.g. thorugh the command git checkout -- <file> will delete all changes, and copies another file over it.

git merge merges all commits. git rebase changes the history by keeping and removing records of commits as asked.

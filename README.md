# git-user

git-user is a convenience wrapper for git commands that sets the author and committer from a predetermined list of usernames.

It is most useful when you are working in another user's account, or as root, and want to commit changes with you as the author and committer. This includes especially git subcommands `commit`, `merge`, `rebase`, etc.

We have used it at End Point since 2010 to track changes in shared locations, the way our co-worker Greg Sabino Mullane did with RCS before we started using Git.

# GitDrago
Custom built version control implemented in Python

## Init

Whenever a repository is considered or created, an object of `GitRepository` is created. This
contains information about the working tree.

The function `repo_find` is critical and searches for the `.git` directory. If there isn't one, it
is not a git repository.



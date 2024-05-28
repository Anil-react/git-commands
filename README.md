# Git Commands Reference

This document provides a reference for commonly used Git commands, including basic operations, branching, collaboration, and more.

## Configuration Commands
- `git config`: Get and set repository or global options.
  - `git config --global user.name "Your Name"`: Set the name attached to your commits.
  - `git config --global user.email "your.email@example.com"`: Set the email attached to your commits.

## Repository Commands
- `git init`: Create an empty Git repository or reinitialize an existing one.
- `git clone [url]`: Clone a repository into a new directory.

## Basic Snapshotting Commands
- `git add [file]`: Add file contents to the index (stage).
- `git commit -m "[message]"`: Record changes to the repository with a message.
- `git status`: Show the working tree status.
- `git diff`: Show changes between commits, commit and working tree, etc.
- `git reset [file]`: Unstage a file while retaining changes in the working directory.
- `git rm [file]`: Remove files from the working tree and from the index.

## Branching and Merging Commands
- `git branch`: List, create, or delete branches.
  - `git branch [branch-name]`: Create a new branch.
  - `git branch -d [branch-name]`: Delete a branch.
- `git checkout [branch-name]`: Switch branches or restore working tree files.
- `git merge [branch-name]`: Join two or more development histories together.
- `git rebase [branch]`: Reapply commits on top of another base tip.

## Collaboration Commands
- `git fetch [remote]`: Download objects and refs from another repository.
- `git pull [remote]`: Fetch from and integrate with another repository or a local branch.
- `git push [remote] [branch]`: Update remote refs along with associated objects.

## Inspection and Comparison Commands
- `git log`: Show commit logs.
- `git show [commit]`: Show various types of objects.
- `git diff [first-branch]...[second-branch]`: Show changes between two branches.

## Remote Commands
- `git remote`: Manage set of tracked repositories.
  - `git remote add [name] [url]`: Add a new remote.
  - `git remote remove [name]`: Remove a remote.
  - `git remote -v`: Show URLs of remotes.

## Stashing Commands
- `git stash`: Stash the changes in a dirty working directory away.
  - `git stash apply`: Reapply the changes stashed.
  - `git stash drop`: Discard the changes stashed.

## Tagging Commands
- `git tag`: Create, list, delete or verify a tag object signed with GPG.
  - `git tag [tag-name]`: Create a new tag.
  - `git tag -d [tag-name]`: Delete a tag.

## Miscellaneous Commands
- `git archive`: Create an archive of files from a named tree.
- `git bisect`: Use binary search to find the commit that introduced a bug.
- `git blame [file]`: Show what revision and author last modified each line of a file.
- `git clean`: Remove untracked files from the working tree.

This is a brief overview of some essential Git commands. Each command comes with a variety of options and parameters that can be used to tailor its functionality to specific needs. For more detailed information, refer to the [official Git documentation](https://git-scm.com/doc).

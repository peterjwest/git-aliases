# Personal git aliases 

## Installation

Add [these](.gitconfig) to your `~/.gitconfig` file.

## Explanation

- `git pushup` - Pushes a new branch, setting the upstream with the same name (this command is unnecessary if you have `push.autoSetupRemote` set to `true`).
- `git pullup [<branch>]` - Pulls the current branch or a specified branch, regardless of whether it is checked out or not
- `git trim` - Prunes remote branches and then removes any _merged_ branches which aren't develop, master or main
- `git destash <name>` - Like `stash pop`, but applies & removes a stash by name
- `git rebranch` - Resets a branch to match origin, useful if someone else has rebased a branch. **Warning**: This will unreference any new commits on the local branch.
- `git uncommit` - Undoes the last commit, leaving the changes staged
- `git agree` - Tells you if the _file tree_ in your current branch matches origin, very useful for rebases
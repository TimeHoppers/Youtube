# Comandos Basicos Terminal
pwd - print current directory
ls <route> - list files and folders
man <command> - show manual of a command
cd <route> - change directory
touch <filename> - create file
cat - show content of file
rm <files> - remove files
rmdir <folder> - remove directories ( only for empty characters )
mv <file> <newRoutes> - Move files and folders to new location
cp <fileSource> <cloneFile> - Copy folders or files.

# Commandos Git
git init - Initialize a github repo.

## Manage history
`git status` - show current folder status.
`git add <files>` - Add files to next commit
`git commit -m "<message>"` - Creates a commit with a new message.
`git log --oneline --graph` - Show history of commits.

## Branches
`git branch` - list of current git branches.
`git switch -c <branch-name>` - Create a new branch an move into it
`git switch <branch-name>` - Moves to a branch
`git checkout <git HASH>` - Moves the HEAD to the commit with a hash.
`git merge <branch>` - Merges two branches
`git rebase <branch>` - executes a rebase.

## Undo Changes
`git revert` - undo the changes up to a commit.

## Remotes 
`git remote -v` - list remotes
`git remote add <name> <url>` - Add a remote.
`git remote remove <name> <url>` - removes a remote.
`git push` - Push changes to remote (Github).
`git pull --rebase` - Download the latest changes of the remote repository
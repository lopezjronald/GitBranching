## Branching example

### Git cheat Sheet

#### Info commands
* `git status` - status of current git repo
* `git config -l` - List configuration of repo
* 'git log ` - log of commits in this repo
* 'git log --oneline` - Compact log listing
* 'git branch' - Display branch information

### Basic Commands
* `git init` - Init a repo in current working dir
* `git add .` - Stage current dir for commits
* `git commit -m "stuff"` - Commit staged data, with message "stuff"
* `git commit` - Commit staged data, enter message in vi editor

### Branching commands
* 'git branch branchName' = Create branch 'branchName'
* 'git checkout branchName' - Go to branch 'branchName'
* 'git checkout -b branchName' - Create and checkout 'branchName'
* 'git pull origin master' - Pull 'master' branch into current branch

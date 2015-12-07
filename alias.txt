Common aliases

> git config --global alias.st status
> git config --global alias.ci commit
> git config --global alias.co checkout
> git config --global alias.cb 'checkout -b'
> git config --global alias.br branch

Cleaning
> git config --global alias.cf 'clean -f'           # clean force
> git config --global alias.cs 'checkout -- .'      # discard changes in working directory
> git config --global alias.unstage 'reset HEAD --' # discard changes in staging area
> git config --global alias.us 'reset HEAD --'

Rebasing
> git config --global alias.reb rebase
> git config --global alias.rbi 'rebase -i'

Logs
> git config --global alias.lol "log --graph --decorate --pretty=oneline --abbrev-commit --all"  # nice logs
> git config --global alias.l log
> git config --global alias.lone 'log -1'
> git config --global alias.last 'log -1'
> git config --global alias.hist 'log --pretty=format:"%h %ad | %s%d [%an]" --graph --date=short' # more nice logs
> git config --global alias.gk '!gitk'

Diffs
> git config --global alias.d difftool

Stashing
> git config --global alias.s stash
> git config --global alias.sl 'stash list'
> git config --global alias.laststashed 'stash apply stash@{0}'    # apply last stashed item without removing from the stash
> git config --global alias.slast stash 'apply stash@{0}'          # same as above

Configurations
> git config --global alias.cg 'config --global'
> git config --global alias.cgl 'config --global --list'

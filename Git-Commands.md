# Git Commands
* ## Git config
  sets username.

* ## Git init
  To initialise a git repository for a new or existing project.\
  *git init in the root of your project directory.*

* ## Git clone
  To copy a git repository from remote source, also sets the remote to original source so that you can pull again.\
  *git clone <:clone git url:>*

* ## Git status
  To check the status of files you’ve changed in your working directory, i.e, what all has changed since your last commit.\
  *git status in your working directory. lists out all the files that have been changed.*

* ## Git add
  adds changes to stage/index in your working directory.\
  *git add*

* ## Git commit
  commits your changes and sets it to new commit object for your remote.\
  *git commit -m”sweet little commit message”*

* ## Git push/Git pull
  Push or Pull your changes to remote. If you have added and committed your changes and you want to push them. Or if your remote has updated and you want those latest changes.\
  *git pull <:remote:> <:branch:> and git push <:remote:> <:branch:>*

* ## Git branch
  Lists out all the branches.\
  *git branch or git branch -a to list all the remote branches as well.*

* ## Git checkout
  Switch to different branches.\
  *git checkout <:branch:> or **_git checkout -b <:branch:> if you want to create and switch to a new branch.*

* ## Git stash
  Save changes that you don’t want to commit immediately.\
  *git stash in your working directory. git stash apply if you want to bring your saved changes back.*

* ## Git merge
  Merge two branches you were working on.\
  *Switch to branch you want to merge everything in. git merge <:branch_you_want_to_merge:>*

* ## Git reset
  You know when you commit changes that are not complete, this sets your index to the latest commit that you want to work on with.\
  *git reset <:mode:> <:COMMIT:>*

* ## Git remote
  To check what remote/source you have or add a new remote.\
  *git remote to check and list. And git remote add <:remote_url:>*
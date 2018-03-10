# git-usefull-command

# Revert changes to modified files.
```$ git reset --hard```

# Remove all untracked files and directories.
```$ git clean -fd```

#git bitbucket command

# To create New Branch
```$ git checkout -b topic_branch```

# To check branch which you are in
```$ git branch```

# To return to master branch or change another branch
```$ git checkout master```

# To merge branch name to your current branch
```$ git merge branch-name```

# To delete branch
```$ git branch -D topic-branch```

# To initialize branch for commit
```$ git add -A```

# To add message to your commit
```$ git commit -a -m "Your Commit"```

# To add your github commit
```$ git push```
```
$ git push heroku master — for first time
$ git push heroku
$ heroku run rake db:migrate
```
```
The most commonly used git commands are:
   add        Add file contents to the index
   bisect     Find by binary search the change that introduced a bug
   branch     List, create, or delete branches
   checkout   Checkout a branch or paths to the working tree
   clone      Clone a repository into a new directory
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   fetch      Download objects and refs from another repository
   grep       Print lines matching a pattern
   init       Create an empty Git repository or reinitialize an existing one
   log        Show commit logs
   merge      Join two or more development histories together
   mv         Move or rename a file, a directory, or a symlink
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects
   rebase     Forward-port local commits to the updated upstream head
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index
   show       Show various types of objects
   status     Show the working tree status
   tag        Create, list, delete or verify a tag object signed with GPG
```
Adding commit
```
$ git status
$ git add -A
$ git commit -m "Finish toy app"
$ git push
```
# deploy heroku



```
$ heroku create
$ git push heroku master
$ heroku run rake db:migrate
$ heroku open
```
# rename app
```
$ git remote rm heroku
$ heroku git:remote -a newname
```
# migration issue
```
heroku run bash --app appname
rake db:migrate
```
# delete app sample
```
$ heroku apps:destroy fierce-mesa-4429 --confirm fierce-mesa-4429
```

check euro on heroic

$ heroku logs --tail
=====================
```
$ git init
do one of this
$ git clone /path/to/repository
or
$ git clone username@host:/path/to/repository
$ git commit -m “First commit”
$ git push
```

# Upload Command
```
$ git status
$ git add .
$ git commit -m "your message"
$ git push
```

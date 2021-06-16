# Git Course

## Main Commands

```
$ git init -> Create an empty git repository
``` 
```
$ git add <file or directory name> -> To stage a specific file

$ git add . -> To add all files not staged

$ git add css -> To stage an entire directory
```
```
$ git commit -m "Commit message in quotes" -> Adding a commit with a message

$ git commit -a -m ˜Add and commit a message in quotes˜ -> Adding and commit with a message
```
```
$ git status -> This command returns the current state of the repository.
```
```
# Running git config globally

$ git config --global user.email "my@emailaddress.com" -> 

$ git config --global user.name "Brian Kerr"

# Running git config on the current repository settings

$ git config user.email "my@emailaddress.com"

$ git config user.name "Brian Kerr"
```
```
$ git branch <branch_name> -> Create a new branch

$ git branch -a -> List all remote or local branches

$ git branch -d <branch_name> -> Delete a branch
```
```
$ git checkout <branch_name> - > Checkout an existing branch

$ git checkout -b <new_branch> -> Checkout and create a new branch with that name
```
```

$ git remote add origin git@account_name.git.beanstalkapp.com:/acccount_name/repository_name.git -> Adding a remote repository with the name of beanstalk

$ git remote -v -> List named remote repositories
```

```
$ git merge <branch_name> -> Merge changes into current branch
```

```
$ git clone <repository> -> Clone a git repository
```

```
$ git pull <branch_name> <remote_URL/remote_name> -> Pull from named remote
```

```
$ git push <remote_URL/remote_name> <branch> -> Push a specific branch to a remote with named remote

$ git push —all -> Push all local branches to remote repository
```

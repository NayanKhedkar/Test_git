Hey this the Test command.

## Connect to git repository

```git remote add origin git@github.com:NayanKhedkar/Test_git.git```

## Pull fresh repo from git hub

```git clone https://github.com/NayanKhedkar/Test_git.git```


## Pull changes from remote to local repository

```git pull ```

Or

``` git pull origin master```

Or

``` git pull origin branch_name ```
 
## Check all branches

```git branch -a```

## Add all change to stage

```git add .```
 
Or

```git add filename_to_add```

## Or directly commit

```git commit -a```

## Check modified files
```git status```

## Commit current changes 

```git commit -m "message to commit"```

## Push changes to remote repository

```git push ```

Or

``` git push origin master```

Or

``` git push -u origin branch_name ```

 ```-u``` to upstream if branch is not on remote then create it. 

### Updates all the remote tracking branches in local repository

``` git fetch ```

### Integrating changes from one branch onto another
#### By rebase:

```git checkout branch_name```

``` git rebase master```

This moves the entire <branch_name> branch to begin on the tip of the master branch

#### By Merge:

The easiest option is to merge the master branch into the feature branch using something like the following:

``` git checkout to_branch_name ```

``` git merge from_branch_name ```

Or, this to a one-liner:

```git merge to_repo_name from_repo_name```
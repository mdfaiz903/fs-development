# git guide

## step 1: (install git in local)

## check it using below command 
```
git --version

```

# Configuration:
## now Config the git in locally
```
git config –global user.name “your_name”
git config –global user.email “your_email"
```
## Check configuration: 

``` git config --list  ```

# start work

```
git init
git add file_name #staging areal
git commit -m give_some_massage #local repo
git push # remote repo
```


# chek status
```
git status or git dif

```

# check  commits history
``` git log / git log --oneline```

To move previous stage (ex: local remo -> staging_area) use command

``` git reset --soft commit_id ```


## mode one commit to another

``` git checkout commit_id ```


## Check branch
``` git branch ```

## Create new branch

``` git branch branch_name ```

## switch branch one to anther

``` git checkout branch_name ```
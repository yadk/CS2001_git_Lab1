# CS2001: 2020-21 Group Project

Some useful tips on how to configure your git project using `terminal` `commands` 

## Configure git 

```
git config --global user.name "Name"
git config --global user.email "email id"
git config --global core.editor "vim"
```

## Setting up the project 
Assuming your group number is "group1"
```
git clone git@github.com:BrunelCS/group1
git remote add group1 git@github.com:BrunelCS/group1
 
#check if it is setup properly
git remote -v
git pull group1 master
```

##### add+commit+push
```
cd group1 && git add . && git commit && git push group1 master
```

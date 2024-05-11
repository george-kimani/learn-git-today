# LEARN GIT TODAY

## Idenfity the git user global within the device
```
  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
```

![alt text](image-6.png)

## Initialize github in a folder

```
# initialize git in learn-github folder

git init

```

![alt text](image-1.png)

## Get the repository / project / folder git status

```
# git status

git status 
```

![alt text](image-2.png)

## Track files within a repository / folder using git (git staging)

```
# git add
git add <image-1.png>

# to view the added / staged file use
git status

```

![alt text](image.png)

### A screenshot of the github staged / unstaged changes 

![alt text](image-3.png)

## Staging all files

### To discovery how to stage all files once use:

![alt text](image-4.png)

```
# stages all files
git add -A
```

![alt text](image-5.png)

# Commit our changes
```
# commit changes 
-m for commit message
git commit -m "learnt github"
```

![alt text](image-7.png)

# An Introduction to Github

We go to github.com and create a repository with the name learn-git-today

## A step by step guide for github

- Go to your repositories

![alt text](image-8.png)

- click on new repository

![alt text](image-9.png)

- create the repository

![alt text](image-10.png)

- push the local changes to github (remote)
```
git remote add origin <url>
git push -u origin main
```

![alt text](image-11.png)

If git (local) hasn't yet been authorized to access github (remote). It shall prompt you for authorization

## Updating the most current version of our repository

We need to stage all files again before commit

![alt text](image-12.png)

Finally commit all changes


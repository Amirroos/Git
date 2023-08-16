# GIT :computer:

## GITHUB: go to github [form chrome](https://github.com/) 

<!-- about git word -->
<h2 align="center"> :warning: Idioms :warning: </h2>

| word | mean |
|---|---|
| repository | A repository in Git refers to a central location where all the files and folders associated with a project are stored and managed. |
|staging area | The staging area in Git refers to a file in your Git directory that stores information about what will go into your next commit.| 
| workign tree | The project is running in git|
| commit | to each of the changes say commit |
|branch|A bunch of commit|
|tag|namming of commit|
<h2 align="center"> :hushed: lingua :hushed: </h2> 

| word | mean |
|---|---|
|master| the default main branch in a repository. |
|head|It is called the last commit|
|origin| server that a local repository was originally cloned from.|

git clone :It is used to create a copy of an existing Git repository from a site or someone or...
 ```sh
$ git clone --branch=master 
or
$ git clone --branch=master --dept
or
$ git clone https://for example 
  ```

## REPOSITORY
<h4>HOW MAKE REPOSITORY raised_hands :</h4>
 
  ```sh
$ mkdir amir
$ cd amir
  ```
(amir is example)<br>


Convert the file to git:
  ```sh
$ git init
  ```
## CONFIGURATION
<h4> HOW TO SET CONFIGURATION :raised_hands: : </h4>
<h5>username:</h5>

  ```sh
$ git comfig --global user.name "example"
  ```

<h5>email:</h5>
  
  ```sh
$ git comfig --global user.email "example@gmail.com"
  ```
## status
<h5>There are three modes for the file</h5>

| untracked | unmodified | modified |
|---|---|---|

<h5>git status:</h5>
shows the state of the working directory and staging area.

## save 
<h4>HOW TO SAVE CIMMIT:</h4>
 
  ```sh
$ git add main.txt
$ git commit -m "commit massage"
  ```
commit massage: Description for changes 

## diff
<h4>HOW TO USE DIFF:</h4>

  ```sh
$ git diff
  ```
can see changes each part.
## log
shows the commit history and details about each commit in a Git repository.
 ```sh
See commit history for the current branch:
$ git log
 ```
  ```sh
Include summary diffstats for each commit:
$ git log --stat
  ```
```sh
Format output to one line per commit:
$ git log --oneline 
  ```
## ignore 
<h4>HOW TO USE GIT IGNORE: </h4>

  ```sh
$ touch gitignore.log
$ nano gitignore.log
write *.log
$git add gitignore.log
$git commit -m "commit massage"
  ```
<h5>gitignore.log</h5>
It is used to tell Git which files or folders to ignore in a project. 

## stash 
<h4>HOW TO USE GIT STASH: </h4>

```sh
$ git add file
$ git stsh
$ git stash show
  ```
<h4>HOW TO BACK FROM STASH:</h4>

```sh
$ git stash pob stash@\{1,2,3...}
  ```
<h5>files that's not in stagig:</h5>

```sh
$ git stash -u
  ```
<h5>gitignore file:</h5>

```sh
$ git stash -a
  ```


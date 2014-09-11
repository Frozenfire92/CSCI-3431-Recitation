# CSCI 3431 - Operating Systems Recitation 1
### September 11 2014

A collection of notes I took during the first recitation for students needing more help or who missed a something.

## Basic Command Line Maneuvering 

Use `man` as prefix to any command for more information on it

```bash
cd # change directory
mv # move files
ls # list files in the current directory
ls -a # list files in the current directory (including hidden or dot files)
ls -l # list files in the current directory in long mode
ls -al # list files in the current directory, in long mode and hidden files shown
pwd # present working directory: displays the directory you are in
cat # concatenate: reads files sequentially and output them to standard output
touch # create file or set permissions and access times of existing file
echo # writes to standard output
> # redirect output
>> # redirect and append output
```

## Git

```bash
git init # make the current directory a git repository
git status # get status of the git repository 
git add <filename> # add the file to the git staging area
git add -A # add all files to the git staging area
git commit -m 'My commit message' # commit files in the staging area
git config --global user.email "my.email@smu.ca" # set your email for git to use in your commits
git config --global user.name "Firstname Lastname" # set your name for git to use in your commits
git log # list commits in this repository
git diff <filename> # see the changes made to the file in the working directory
git checkout -- <filename> # grabs the file as it was in the most recent commit and applies it to the working directory
git checkout -- * # grabs all files in the most recent commit and applies it to the working directory
```

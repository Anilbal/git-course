```
Document from link:https://docs.chaicode.com/home-for-programmers/
```

## Git
Git is a version control system that is used to track changes to your files. It is a free and open-source software that is available for Windows, macOS, and Linux. Remember, GIT is a software and can be installed on your computer.

## Github
Github is a web-based hosting service for Git repositories. Github is an online platform that allows you to store and share your code with others. It is a popular platform for developers to collaborate on projects and to share code.

## Repository
A repository is a collection of files and directories that are stored together. It is a way to store and manage your code. A repository is like a folder on your computer, but it is more than just a folder. It can contain other files, folders, and even other repositories. You can think of a repository as a container that holds all your code.


# Git Commands
### git --version
It helps to know what version of git you are using.

### git status
It provides an overview of the current state of your working directory and staging area. It shows which files have been modified, which are staged for the next commit, and which are untracked (new files not yet added to version control). 

### git config
```
git config --global user.email "abc@gmail.com"
git config --global user.username "Abc 123"
git config --list

```
## Project or git starting (Look into diagram.png first to know work flow of git)

### git init
git init command will create a new folder on your system and initialize it as a git repository. This adds a hidden .git folder to your project.

### git add 
You can use command to add single files : ``` git add filename/foldername ```
Or
You can use command to add the files at a time : ``` git add . ```

### git commit 
After adding files , you have commit show when and which files are commited by user 
``` git commit -m "your message" ```

### git log
This command will show you the history of your repository. It will show you all the commits that were made to the repository.

You can use ``` git log --oneline ``` to make all log in single line.



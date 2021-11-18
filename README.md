

<h1 align="center"> Git & GitHub for Absolute Beginners 💥</h1>

### **Complete Guide to Git and Github**

<div align="center">

<a href="https://github.com/mukeshdani/Git-GitHub"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/mukeshdani/Git-GitHub?color=2b9348"></a>
<a href="https://github.com/mukeshdani/Git-GitHub"><img src="https://img.shields.io/badge/language-English-green.svg"></a>

</div>

**[Git & GitHub  ~ Resources 👉](https://github.com/mukeshdani/Git-GitHub)** *Using Easy English language*

In this Repo we are learning the basics of [Git & GitHub](https://en.wikipedia.org/wiki/GitHub), how it works, etc.


## Technology 👇

-[GitHub](https://github.com/mukeshdani/Git-GitHub) 
 ## Platform 👇

-[GFG](https://www.geeksforgeeks.org/ultimate-guide-git-github/)

-[Visual Studio code editor](https://code.visualstudio.com/)

### contact 
💼 Pull requests help you collaborate with me [issues and pull requests](https://github.com/mukeshdani/Git-GitHub/pulls) :)

 💼 if you have any doubt? do reach, [email](mailto:mukeshdani00@gmail.com) :)

<h1 align="center"> Introduction 💥</h1>

In this Repo we are learning the basics of Git & GitHub, how it works, etc.

# What is Git?
Git is a free, open-source version control software. It was created by Linus Torvalds in 2005. This tool is a version control system that was initially developed to work with several developers on the Linux kernel.

<img align="center" alt="GIF" src="Mukesh.png" width="100%" height="300" />


## **Git Repositories**
If we want to start using Git, we need to know where to host our repositories.

A repository (or “Repo” for short) is a project that contains multiple files. In our case a repository will contain code-based files.

There are two ways you can host your repositories. One is online (on the cloud) and the second is offline (self-installed on your server).

There are three popular Git hosting services: **GitHub** (owned by **Microsoft**), **GitLab** (owned by **GitLab**) and **BitBucket**.

## **why we need it**
  * Git makes it easy to contribute to open source projects ☺️

  * Documentation 😍

  * Integration options

 * Track changes in your code across versions 🖥️

 * Showcase your work 😄


## **Git installation**

 * install Git and GitHub with apt-get

     sudo apt-get install git

* verify that Git is installed correctly

    git --version

* set a default username and email when you’re going to save your work.

    git config --global user.name "MUKESH DANI"
    git config --global user.email "mukeshdani00@gmail.com"



## **Working with GitHub projects**
We’ll work with GitHub projects in two ways.   

**1 👉** : *Work on your project locally then create the repository on GitHub and push it to remote.*

**Initialize directory :**

### git init 
initializes your directory to work with git and
makes a local repository. .git folder is made

*OR*

### git clone http_url 
This is done if we have an existing git repository.


**Connecting to repository :**

### git remote add origin http_url/ssh_url 
connect to central repo to push/pull
pull means transferring the changes on the central repository to your local repository. push is the vice versa of pull.

### git pull origin master
Always first pull contents from the central repo before pushing so that you are updated with other team members’ work.
Here, master means the master branch (in Git).

**Now time To add a file to central Repository:**
First, your file is in your working directory, Move it to the staging area by typing:

### git add -A (for all files and folders)
 To add all files only in the current directory
### git add .
To add all files only in the current directory
### git status 
The first thing you need to do is to check the files you have modified.
    

### git commit -a -m "message for commit"
Now that we have added the files of our choice, we need to write a message to explain what we have done. This message may be useful later if we want to check the change history.

### git push origin master -> pushes your files to 
github master branch
### git push origin anyOtherBranch -> pushes any 
   other branch to github.

### git log ;
 to see all your commits

HEAD -> pointer to our latest commit.


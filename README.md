# Github Learning - create a local repo and push to remote

- **OS**: Windows 10
- **Software**: Git Bash, Visual Studio Code, 
- **Target**: Create a local repo,edit file locally,then push to remote for host.

Table of this content:

- [Step 1: Get tools handy](#Step)
- [Step 2: Create a local repo with Git Bash](#step-2-create-a-local-repo-with-git-bash)

## Step 1: Get tools handy

First we need know the **difference** between Git Bash and Git CMD, or even Git GUI.

- Git Bash
>emulates a bash environment on windows. It lets you use all git features in command line plus most of standard unix commands. Useful if you are used to Linux and want to keep the same habits.

- Git CMD
>like regular Windows command prompt with the git command. It lets you use all of Git features through command line. Useful if you are already familiar with Windows cmd and you only work on Windows.

- Git GUI
>a Graphical User Interface letting you use Git without touching command line. It is an alternative among other Git clients.

Now as I know this, so when I face installation Git on my computer, I choose only use Git in Git Bash because I want to try unix style though I don't even konw windows CMD right now.

This is why the tool I use is Git Bash, not Git CMD.

Download the latest version of Git for windows at https://git-scm.com/downloads

Download the latest version of Visual Studio Code for windows at https://code.visualstudio.com/Download

## Step 2: Create a local repo with Git Bash

I want to make this repo locate at `d:/learn-github` on my local computer, so first we create a directory here:
```
mkdir d:/learn-github
```
then I change our current dir there:
```
cd d:/learn-github
```
then I init this repo:
```
git init
```
After this , I have done the job. 

As I need capture this so I make another dir so I can put a screenshoot image here.
```
mkdir images
```
And here is the image:

![init-repo](d:/learn-github/images/init-repo.png)





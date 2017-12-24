# Learning how to use Git and Github
*Written by: YOUR_NAME_HERE, Core Team 17*

## What is Version Control?
> Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.
>
> -- [<cite>Pro Git 2nd Edition (2014)</cite>](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)


*Further Readings:*
- Additional
    - [Atlassian - What is Version Control?](https://www.atlassian.com/git/tutorials/what-is-version-control)
- Optional Readings
    - [Wikipedia - Version Control](https://en.wikipedia.org/wiki/Version_control)
    
### What is a Local Version Control System?
> ... programmers long ago developed local VCSs that had a simple database that kept all the changes to files under revision control.
>
> -- [<cite>Pro Git 2nd Edition (2014)</cite>](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)

E.g. of interactions of local VCS
![Example of interactions of a Local VCS](https://git-scm.com/book/en/v2/images/local.png "Example  of interactions of a Local VCS")


### What is a Centralized Version Control System?
>These systems ... have a single server that contains all the versioned files, and a number of clients that check out files from that central place.
>
> -- [<cite>Pro Git 2nd Edition (2014)</cite>](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)

E.g. of interactions of a Centralized VCS
![Example of interactions of a Centralized VCS](https://git-scm.com/book/en/v2/images/centralized.png "Example of interactions of a Centralized VCS")

### What is a Distributed Version Control System?
>In a DVCS , ... clients ... fully mirror the repository. 
>
>Thus if any server dies, and these systems were collaborating via it, any of the client repositories can be copied back up to the server to restore it.
>
>Every clone is really a full backup of all the data.
>
> -- [<cite>Pro Git 2nd Edition (2014)</cite>](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)

E.g. of Interactions of a Distributed VCS
![Example of Interactions of a Distributed VCS](https://git-scm.com/book/en/v2/images/centralized.png "Example of Interactions of a Distributed VCS")


## What is Git?
Git is a version control system that allows for easy collaboration. It's awesome, and it is a crucial tool for any analyst, developer, or data scientist, beginner or otherwise!
Learn it and learn it well, because git will definitely save you when you most need it!

This guide is a condensed version of Pro Git, available on the git official website [here](https://git-scm.com/book/en/v2).

### How does Git think in Snapshots?
>Git thinks of its data more like a set of snapshots of a miniature filesystem. 
>
>Every time you commit, or save the state of your project in Git, it basically takes a picture of what all your files look like at that moment and stores a reference to that snapshot. 
>
>To be efficient, if files have not changed, Git doesn’t store the file again, just a link to the previous identical file it has already stored.
>
>Git thinks about its data more like a stream of snapshots.
>
> -- [<cite>Pro Git 2nd Edition (2014)</cite>](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)

E.g. of how data is stored as snapshots over time
![Example of how data is stored as snapshots over time](https://git-scm.com/book/en/v2/images/snapshots.png)

### Why are most Git operations local?
https://git-scm.com/book/en/v2/Getting-Started-Git-Basics

### How does Git ensure data integrity?

### How does Git allow recovering of data and undoing things?

### What are the 3 states and 3 sections of Git?
> Git has three main states that your files can reside in: committed, modified, and staged. 
>
>Committed means that the data is safely stored in your local database. 
>
>Modified means that you have changed the file but have not committed it to your database yet. 
>
>Staged means that you have marked a modified file in its current version to go into your next commit snapshot.
>
> -- [<cite>Pro Git 2nd Edition (2014)</cite>](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)

E.g. of 3 states of git
![Example of the 3 states of git](https://git-scm.com/book/en/v2/images/areas.png)

The three main sections of Git:
- The Git Directory
    >The Git directory is where Git stores the metadata and object database for your project. This is the most important part of Git, and it is what is copied when you clone a repository from another computer.
    >
    > -- [<cite>Pro Git 2nd Edition (2014)</cite>](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)
- The Working Tree
    >The working tree is a single checkout of one version of the project. These files are pulled out of the compressed database in the Git directory and placed on disk for you to use or modify.
    >
    > -- [<cite>Pro Git 2nd Edition (2014)</cite>](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)
- The Staging Area
    >The staging area is a file, generally contained in your Git directory, that stores information about what will go into your next commit.
    >
    > -- [<cite>Pro Git 2nd Edition (2014)</cite>](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)

### How to install Git?
Proceed to the offical website [here](https://git-scm.com/downloads).

### What are the things to note for first time setup of Git?
>Git comes with a tool called git config that lets you get and set configuration variables that control all aspects of how Git looks and operates. 
>
> -- [<cite>Pro Git 2nd Edition (2014)</cite>](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)

Variables and their storage:
>These variables can be stored in three different places:
> 1. `/etc/gitconfig` file
>       - Contains values for every user on the system and all their repositories. 
>       - If you pass the option `--system` to `git config`, it reads and writes from this file specifically.
>
>2. `~/.gitconfig` or `~/.config/git/config` file
>       - Specific to your user. 
>       - You can make Git read and write to this file specifically by passing the `--global` option.
>
>3. `config` file in the Git directory (that is, `.git/config`) of whatever repository you’re currently using
>       - Specific to that single repository.
>
> -- [<cite>Pro Git 2nd Edition (2014)</cite>](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)

Your identity:
>The first thing you should do when you install Git is to set your user name and email address. This is important because every Git commit uses this information, and it’s immutably baked into the commits you start creating
>
>```
>$ git config --global user.name "John Doe"
>$ git config --global user.email johndoe@example.com
>```
>
> -- [<cite>Pro Git 2nd Edition (2014)</cite>](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)

To check your settings (at any time):
>```
>$ git config --list
>```
>
> -- [<cite>Pro Git 2nd Edition (2014)</cite>](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)

### How to access the help manual while using Git?
To check the manual (at any time), where `verb` is a command or action:
>```
>$ git help <verb>
>$ git <verb> --help
>$ man git-<verb>
>```
>
> -- [<cite>Pro Git 2nd Edition (2014)</cite>](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)


## Git Basics
### How to initialize a Git repository in an empty project directory?
In your project's empty directory, type:
>```
>$ git init
>```
>This creates a new subdirectory named .git that contains all of your necessary repository files – a Git repository skeleton. At this point, nothing in your project is tracked yet.
>
> -- [<cite>Pro Git 2nd Edition (2014)</cite>](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository)

### How to make Git track existing files in a non-empty project directory?
Assuming you have files that have the .c extension, and also a LICENSE file:
> ... you should probably begin tracking those files and do an initial commit. You can accomplish that with a few `git add` commands that specify the files you want to track, followed by a `git commit`:
>```
>$ git add *.c
>$ git add LICENSE
>$ git commit -m 'initial project version'
>```
> -- [<cite>Pro Git 2nd Edition (2014)</cite>](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository)

### How to check the Status of a Git repository?


### How to do an initial commit?

### How to clone an exisitng repository?

### 


## Git Branching

## Git Basics

- [Github 15 mins tutorial](https://try.github.io/levels/1/challenges/1)
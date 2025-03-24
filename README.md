An Operating System is a system software that manages the computer's resources and provides interface and functionalities for the users.

major 3 desktop operating system
1. Linux
2. Mac Os
3. Windows 


VERSION CONTROL SYSTREM (VCS)
A version Control System (VCS) provides an automatic way to track changes in software projects,
giving creators the power to view previus versions of files and directories, develop speculative features without disrupting the main development, securely backup
the project and its history and collaborators easily and conveniently with others.

Family line leading to git:
!. RCS
2. CVS
3. Subversion
Git is an Open source version control system that allows you to keep track of the changes that we make to our file, save your changes, merge and retrieve your changes.
Git was dveloped by Linux Creator Linus Torvalds to host the Linux Kernel. 
After installation of Git.

* To know if your system has git intalled use the command:
 - which git

* This command displays the installed Git version on your system.
  - git version

* We need to tell git who we are;
These configurations allow git to identify your changes by name and email address.
 - git config --global user.name "***********"
 - git config --global email.name "***********"


* Making a directory 
    -  mkdir -p (name of the directory)
* Changing Directory
    - cd (name of the directory)
* To show list of files
    - ls ( This will show all the list of files there is)
* To list all the files and directories on your present directory
    - ls -a 
* initializing the repo
    - git init
* To create a file (Linux)
    - Touch file name .extension eg. Touch index.html 
* To check for untracked and uncommitted files
    - git status 
* To add untracked files 
    - git add -A (This add all files that are untracked, even if there is just only one)
	We can also add untracked files individually:
	   - git add (the name of the file that you want to add)
* To remove a created file
    - rm filename   eg. rm index.html 
* To commit your file
    - git commit -m + a short message or purpose of committing
	eg. git commit -m index.html "index"
* To view commit history
    - git log
 * To create a new branch
     - git branch 'name of branch'
* To switch to new branch
    - git checkout 'branch name'
* To create and also switch to a new branch
    - git checkout -b 'branch name'
* To list all branches created
    - git branch 
*  To upload commit to git-hub
    - git push origin main
*  

 





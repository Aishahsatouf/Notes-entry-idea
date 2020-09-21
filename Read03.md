# Intoduction to Git
**What is Git?**
Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it.

**what it allows you to do ?**

feature | explenation
--------|------------
Snapshots | chage project's version
local operation | find necessary information in local resources and save it 
track changes | track commited changes in each directory
loss data | menimize data losing 
statuse | knowing if directory is modefied or not 

## How it works?
![stages](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)

**go to Git website to know more** [Git](http://mac.github.com/)
## Customization
1. **Configuration of Variables**
    
    Git tool called git config allows the setting of configuration variables
 
 2. **Identity Setting**  
 Type the following into Terminal or Command Line:

     After installing, set the user name and email address,Type the following into Terminal or Command Line:
      
      git config --global user.name "Jane Smith"

       git config --global user.email "example@email.com"
 ## Check Settings
 To check settings, use the git config --list command.

Example:

*$ git config --list

*user.name=Jane Smith

*user.email=example@email.com

*color.status=auto

*color.branch=auto

*color.interactive=auto

## Getting Help

There are three ways to get more information according commands:

*git help command

*git command --help

*man git-command
# setting up commands 
 1.**Importing**
 
 command | response
 --------|---------
 switch to project | cd test (cd =changedirectory)
 use git init command | git init
 start track repository | git add * . c then git add LICENSE then git commit -m "any message"

 2.**cloning**
   use command git clone followed by the clone command URL 

3.**saving changes**
  
  after cloning a repository, files have tracked status and are unmodified because they have been checked out but not edited
![visual example sumarises the life cycle of file status](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)

3.**checking status**
  utilise the comand *git status* 

4.**Tracking and staging a new file**
 *single file | git add file name
 all files | git add *
 *git status 

 5.**commit a file**
  use the command *git commit -m "your message"*

  6.**pushing changes**
   git push origin master 

   
 

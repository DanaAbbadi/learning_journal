[Home page](https://danaabbadi.github.io/learning_journal/)
# Introduction to Git
![git](https://miro.medium.com/max/4400/1*oMC83-7fB27k1tTMxDfRaQ.png)

Git is defined as a version control technology, which is acting as a tracker for tracking changes. Certain source code files incur changes which are easily tracked with the Git tool. In Git, it works as a complete file-based system. With the help of Git technology, files can be easily reverted to the earlier versions. When looking for a system that can easily restore any file which got deleted, then Git performs well.

Git is a distributed version-control system for tracking changes in source code during software development. Because Git allows for multiple mirrored repositories, programmers working in teams can collaborate with each other in various ways to complete a joint project.

To summerize This, Git is defined as a file change tracker system which even tracks any coded line easily. When using this system, a folder gets created in the beginning which is called *repository*. Under this folder, every detail about the file is stored. With the help of this folder, it is easy to store the data which are helpful in tracking any file.

![git2](https://www.udemy.com/blog/wp-content/uploads/2015/08/image066.png)

## Getting Started
First, you need to install git on your PC, click [here](https://git-scm.com/download/win) to install it according to your PC operating system.

After making sure Git has been installed, you should perform some configuration steps, you will only have to do it once. Statr by opening Git and foolow the bellow instructions:
1.  **git config** : to allow the setting of configuration variables that control aspects of Git’s operation

2. **git config --global user.name "your name"** 
   **git config --global user.email "your.email@email.com"**
   The previous commands will set the user name and email address, which will be used for every Git commit.

## Setting up a Git Repository

* You can create a copy of an existing Git repository from a your Github account by using the clone command with a repository’s URL: 
**$ git clone https://github.com/test mydirectory**

* To view your files in the repository type: **ls** , make sure you are in the correct directory by typing **pwd** 
* you can edit your code in any text editor you want by typing **code .** 

## How to push your edits to Git hub:

All you need is three simple steps:
1. **git add .** : it will view changes

2. **git commit -m "type a massage"** : will save changes

3. **git push origin master** : will push changes to Github



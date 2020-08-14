# LearningGitHub
Learning the GitHub &amp; Repl.it workflow that will be used during this course. 

:pushpin: Learn to use GitHub  
:pushpin: Run a simple Java program in Repl.it  
:pushpin: Create your own Java Program  

## :one: make sure to sign up for GitHub account using your school username/password.  I will add you to our GitHub team.  

## Version Control
- An important feature of Git is called version control. Version control keeps a history of changes to the code as well as managing those changes.  You may notice some new words being used.  **branch**, **master**, **fork**, **commit** and **push**

1. The **master** branch usually refers to the repository where the default devlopment branch is located.  

2. A **branch** is a parallel version of a repository. It is contained within the repository, but does not affect the primary or master branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the master branch to publish your changes.

3. To **fork** a repository is a personal copy of another repository.  You usually do not have access to alter someone else's code, thus forking a repo allows you to make changes without altering the working version.  

4. A **commit**  or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID that allows you to keep record of the specific changes commited along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made.

5. To **push** means to send your committed changes to a remote repository on GitHub.com. For instance, if you change something locally, you can push those changes so that others may access them.

For this course we will be working mostly in the main/master branch.  There is limited need to use a development branch unless we have a larger project or one that is already in production.  


## Workflow

Our workflow will be as follows:  

-> Starter code is in a repository on GitHub  
-> **fork** the repo to make a personal copy of it on your own account (you can keep the name if you want)  
-> In repl.it. Create a new repl by choosing "Import From Github". If you haven't connected your account, do this now.  GitHub will authorize Repl.it's access to your repos.   
-> Add / change / do whatever you need with the code.  While Repl.it will autosave your work and keep it within the site, you will also want to **commit** & **push** your changes up to GitHub.  Make sure to make a comment to what you changed.   


## Your first Java program.  

There is code called `FirstProgram.java` in the repository.  

Get it up an running in Repl.it.  

#### Add the following things to the program: 

1. Using 3 `System.out.println()` statements, print your name, least favorite color, and your favorite (appropriate) dad joke.  
2. Change the for-loop so that Omaha Central is printed 10 times.  

# Welcome to part 3 of the tutorial

<br>
Everybody likes some quality of life to make work a little better. <br>For working with Github alot, the internet webpage is not optimal.<br> Luckily are there various tools to help us, one of these tools is Visual Code Studio (VCS).
<br><br>
VCS is a source-code editor made by Microsoft and can run on Windos, Linux and macOS. It features debugging, syntax highlighting, snippets, code fractoring and is even embedded in git. <br>Thereby are there alot of extensions available online to customise VCS to your needs.<br> In this tutorial the installation to creating and using git will be explained.<br> It is also possible to run various commands in the terminal or even python scripts.<br><br>

# Contents

- Installation
- Extensions
- Overview of Visual Code studio
- Accesing a github
- Making branches and adjust codes
- Pull requests
- Reviewing
- Final note & Whats next

<br><br>

## Installation

Like the most programs, it can be easily installed by using the internet.<br> click [here](https://code.visualstudio.com/) for a link to download VCS. <br>
Complete the installation by using default settings.

![image](images/Download.png)

<br><br><br>




## Extensions

Before we start the whole tutorial lets hook you up with some upgrades, lets install a few extensions.<br>
Extensions are little software packages who can install new features of make some quality of life changes.<br>

This can be an Interprentor for a piece of code (R, C++, python, Java), a proofreader for spelling mistakes or an extension who makes markdown easier for you. <br>
 It is worth it, to look online which are avaialble and suit your needs.<br>

Search for the following extensions by clicking on the extension button in the left bar. ![image](images/Extension.png)
- Github Pull Requests and Issues.
- Github Repositories.
- Python.

![image](images/install_extension.png)
<br>
<br>

## Overview of VSC

VCS contains alot of awesome features but can be quite overwhelming in the start.<br> Luckly we already installed some extensions for quality of life.<br>
The following gives a small overview of all functions of the tabs in VCS.<br>


- Explorer: In this  tab are all files of the current github repository.<br> This is currently still empty, but not for long! <br>
- Search: A search function for in your github repository.<br>
- Source controll: If you edited and saved a file from a github, is here your change to make an pull request or to commit it directly.<br>
- Run and debug: Is for running files, for example "hello_world.py".<br>
- Extensions: A place where you can go shopping for new plugins.<br>
- Remote exporer: An overview of previous githubs where you have been.<br>
- Github: Here is the real magic.<br> Every github repository you own or are admin for will notification be sended to this tab.<br> when a person makes a pull request, issue, review etc.<br> You will get an automated message here.<br> With this you can easily keep an eye on all your (team)projects.<br>

![image](images/layout.png)

On the top bar of VSC are various tabs which can be quite useful.<br>
It's also possible to open a terminal and run various codes. <br>

On the bottom of the window is the workspace and branch you are working in. <br>
![image](images/onderste_balk.png)


<b> But enough talking, lets get into some action!<br><br><br> </b>


<br>

# login with Github

Since we want to work with gubhub, one of the items where Visual code studio in shines, we have to tell them who we are. <br>

make sure you have a Github account and are logged in the website of github  ```https://github.com/ ```

- click on the github icon. ![image](images/github_icon.png)
- click on Sign in

![image](images/login.png)

Following a popup should appear asking for authorisation.
- click on authorize github

![image](images/Authorize_application.png)

Continue and authorize Github

In case you are not logged in, follow the direction of the website.<br>
When the login does not popup continue with the tutorial. Later when you open and fork a repository VS Code will have to let you login.
<br><br><br>
# forking & editing a file

More often do you think items can be better from an already existing code.<br>
With Forking, are you copying someone directory to make changes and save it as your own.

there are easier ways to do so. 
for example by this [tutorial](https://doc.fireflymigration.com/working-with-github-fork-in-visual-studio.html), but we follow the tutorial beneath.


open the atgm github tutorial pages you are reading right now in VCS by doing the following:<br>
- click on the green button ![image](images/open_remote_repository.png)
- on the top of your screen should a window pop up with multiple choices.
- click on ``` open github repository ```
![image](images/open_remote_repository2.png)
- fill in the url extension of the github repository, ``` Avans-ATGM/Github_Tutorial ```

You have now locally openend a github public repository in VCS.  now lets change some files and make a fork by doing the following steps.

Go click on examples and then nucleotide_counter.py


when you clicked on this file a window should pop up.
In this is it possible to edit files so lets start and make a small edit
- make a small edit
- save the file by ctrl-s or click on file and then safe
- go to source control

 ![image](images/source_control.png)

- if you click on your edited file you see what all is changed.

![image](images/viewingchanges.png)

- click on commit with the upper button ![image](images/commit.png)

Since we dont have any right to this github repository, it will ask us to make an fork request instead
![image](images/forking.png)

- click on fork repository 
- VCS studio is now asking for a branch name.

a branch is a different version then the main. so you can keep the original in case you have made errors.
- it will ask to switch to the fork and click on ``` switch to fork ```
![image](images/switch_branch.png)

Github will ask for a new branch name, which you have to fill in and press enter
![image](images/creating_fork.png)


Now you have a forked github repo in your own github account.
In this are you allowed to make all sorts of changes to your own liking.

since you didnt own the github repository previously, you will have to save the file again.
- save the file
- commit the file by source control and give it a proper name followed by the commit button ![image](images/commit.png)



# pulling & reviewing

a pull request is the act of merging a branch into the main branch.
You can only do this when you are an admin of a github repository which is always the case for your own repositories.
lets make a pull request for our created branch of the forked github repository.

- Click on create pull request under source control  ![image](images/create_pull_request.png)
- this should give a new window where you have to give some information

![image](images/making-pull-request.png)
- edit the tab accordingly
- scroll a little bit down and click on ![image](images/create.png)

When working alone it does not seem that much interesting but it can be quite handy when working with different versions or adding new features. with this you can for example first fully test all your scripts before merging it to the main branch.

When not working alone can other admins or owners of a github repository can see what you have changed and review your edits before accepting it & merging it into the main branch.<br>

In this case are you going to review your own changes, just to see the possibilities.

- click on the files in the tab Github pull request ![image](images/pull_request_button.png)
- click on your active pull request.
- here you have various actions to review the pull request.
- When you click on Merge pull request, the branch will be merged into the main branch.

It is also possible to review and give comments.

![image](images/reviewing1.png)

- click on the files and then examples
- click on nucleotide_counter.py
- see the changes which has occourd
- hover with the mouse over the white strip to give out a comment.

![image](images/commenting1.png)

![image](images/commenting2.png)

- other admins can read all the comments, even in VS Code and keep the conversation going 
- it is also possible to make suggestions of changes

In the total pull request review will all comments be noted down

![image](images/commenting3.png)

- click on merge pull request if you are happy with it.
- remove the branch since we dont need it anymore. 
![image](images/delete_branch.png)

 you still have to switch from branch. it doesnt exist anymore but it is still here

 To switch from branch:
 - click on the blue ``` Test_delete_later``` button
 - a pop up window above should appear
 - click on the main branch



![image](images/switch_branches.png)


<br><br>
<br>
<br>
<br>
<br>

## branches

Working directly on someone else's main branch should not be possible unless you are the owner or the admin of the repository.<br> Thereby it is also incredible rude to just change someone else's work. <br> It is also good practise to work in branches.<br><br>
You can see branches as a copy of the main where a new feature or version will be implemented and tested before merging it back to main. <br> With this you can safely test codes or debug it while other people work on a different feature, in a branch from main.<br>
![image](images/branches.png)




## Final note & Whats next

So incase you are not convinced yet to work with github, here are a few reasons why:
- Always have a backup of your code.
- You can always revert changes incase it doesn't work out.
- It is easier to see what changes when working with collaborators.
- Multiple cool advanced options, for example to test the code when you created a commit.
- Overview of issues and a task managers.

### future reading

In case you really do like Visual code Studio, you can also run python or other coding languages in it.
click [here](https://code.visualstudio.com/docs/languages/python) for more information. 




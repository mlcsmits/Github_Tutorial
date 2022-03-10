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

## Overview of VCS

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

On the top bar of VCS are various tabs which can be quite usefull.<br>
It's also possible to open a terminal and run various codes. <br>

On the bottom of the window is the workspace and branch you are working in. <br>
![image](images/onderste_balk.png)


<b> But enough talking, lets get into some action!<br><br><br> </b>

# even is het groot. heb de github tutorial aangepast op Mike's opmerkingen. Het verschil is dat ik nu een account heb gebruikt zonder rechten in de github tutorial
<br>
<br>
<br>
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

In case you are not logged in, follow the direction of the website.
<br><br><br>
# forking & editing a file

More often do you think items can be better from an already existing code.<br>
With Forking, are you copying someone directory to make changes and safe it as your own.

there are easier ways to do so. 
for example by this [tutorial](https://doc.fireflymigration.com/working-with-github-fork-in-visual-studio.html), but we follow the tutorial beneath.


open the atgm github tutorial pages you are reading right now in VCS by doing the following:<br>
- click on the green button ![image](images/open_remote_repository.png)
- on the top of your screen should a window pop up with multiple choises.
- click on ``` open github repository ```
![image](images/open_remote_repository2.png)
- fill in the url of the github repository, ``` https://github.com/Avans-ATGM/Github_Tutorial ```

You have now locally openend a github public repository in VCS.  now lets change some files and make a fork by doing the following steps.

Go click on examples and then nucleotide_counter.py

![image](images/nucleotide_counter_file.py.png)

when you clicked on this file a window should pop up.
In this is it possible to edit files so lets start and make a small edit
- make a small edit
- safe the file by ctrl-s or click on file and then safe
- go to source controll 

 ![image](images/source_control.png)

- if you click on your edited file you see what all is changed.

![image](images/viewingchanges.png)

- click on commit with the upper button ![image](images/commit.png)

Since we dont have any right to this github repository, it will ask us to make an fork request instead
![image](images/forking.png)

- click on fork repository 
- VCS studio is now asking for a branch name.

a branch is a different version then the main. so you can keep the original in cases that you have made errors.
- it will ask to switch to the fork and click on ``` switch to fork ```
![image](images/switch_branch.png)

Github will ask for a new branch name which you have to fill in and press enter
![image](images/creating_fork.png)


Now do you have a forked github repo in your own github account.
In this are you allowed to make all sorts of changes to your own liking.

since you didnt own the github repository previously, you will have to safe the file again.
- safe the file
- commit the file by source controll and give it a proper name followed by the commit button ![image](images/commit.png)



# pulling & reviewing

a pull request is the act of merging a branch into the main branch.
You can only do this when you are an admin of a github repository which you are always of your own reposiotry.
lets make a pull request of our created branch of the forked github repository.

- Click on create pull request under source controll  ![image](images/create_pull_request.png)
- this should give a new window where you have to give some information

![image](images/making-pull-request.png)
- edit the tab accordingly
- scroll a little bit down and click on ![image](images/create.png)

When working alone it does not seem that much interesting but it can be quite handy when working with different versions or adding new features. with this you can for example first fully test all your scripts before merging it to the main branch.

When not working alone can other admins or owners of a github repository can see what you have changed and review your edits before accepting it & merging it into the main branch.<br>

In this case are you going to review your own changes, just to see the possibilities.

- click on the files in the tab Github pull request ![image](images/pull_request_button.png)
- click on your active pull request.
- in this you you have various actions to review the pull request.
- When you click on Merge pull request, the branch will be merged into the main branch.

It is also possible to review and give comments.

![image](images/reviewing1.png)

- click on the files and then examples
- click on nucleotide_counter.py
- see the changes which has occourd
- hover with the mouse over the white strip to give out a comment.

![image](images/commenting1.png)

![image](images/commenting2.png)

- other admins can read all the comments, even in VCS and keep the conversation going 
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



# dit is de oude gedeelte. hiervan delen combineren
## Getting access to a github repository

Remember the repository you made, lets open it up.<br>
click on the green box in the left under box. ![image](images/github_knopje.png)<br>

This will open a small terminal above and click on "open remote repository".<br>
![image](images/open_repository_box.png)
 
In this window you fill in the URL of the github repository you created earlier.<br>
![image](images/open_repository_2.png)


Every time you have added a github repository, you dont have to search the url again.<br>
When you click on the the remote explorer tab, you will find a overview off all repository you have worked in.<br>
You also see if you need to update a repository locally in VCS.<br>
In VCS it is also possible to look up pull requests and access pulled repositories.<br>
When you have done this, it is possible to view and edit all files in the explorer tab.<br>

![image](images/all_repositories.png) <br><br>


## Making branches and adjust codes

Working directly on someone else's main branch should not be possible unless you are the owner or the admin of the repository.<br> Thereby it is also incredible rude to just change someone else's work. <br> It is also good practise to work in branches.<br><br>
You can see branches as a copy of the main where a new feature or version will be implemented and tested before merging it back to main. <br> With this you can safely test codes or debug it while other people work on a different feature, in a branch from main.<br>
![image](images/branches.png)


Lets create our first branch on someone else's github repository!<br>
- Open the repository of this github tutorial or the github repository of someone else in the previous parts of the tutorial. <br>
````
https://github.com/Avans-ATGM/Github_Tutorial
````
- Create a new branch to work in and give it a usefull name.<br>
A new branch can be opened by clicking on this button below ![image](images/branch_button.png) <br> and click on ``` + Create new branch ``` <br>
Since we are testing, lets call it 
````
test_[your_username]
````

So now we have a copy from the mainbranch. In this we can code and give adjustments. <br> After we edited or created some new files we can merge it back into the main by creating a pull request
<br>
In the Examples directory is the file "Nucleotide_Counter.py" which can be edited or viewed for other interesting files. <br>

Here we see a simple for loop to count all the nucleotides. Since we are pretty good Python coders we can improve it. ![image](images/nucleotide_counter.py.png)

Lets make it a dictionary loop to reduce the number of lines.<br> It should look something like this.

![image](images/Nucleotide_counter_edited.png)

Safe all your work locally by clicking on file and then safe, or close the window and a message will pop up. <br><br>

## Opening a pull request
When you have made a fork or branch with a new feature and it's finished, you can merge it to the main branch. <br> In this process all changes, deletions and additions will be added to the files you edited in the main branch for everyone to use.<br>
We have edited the python code to be more efficient and have lesser lines. 
Lets make a pull request to merge it back to the main branch.

- click on the Source controll tab.
- click on commit to safe all changes to your current branch.
- click on create pull request. <br> 

The following window should pop up.<br>
In this window is it possible to define to what branch your branch should be merged with.<br>
Remember to give the pull request a meaningfull name (fixing typo's in github_tutorial.md)<br> In the description you can give a more detailed explaination about what and why you changed codes.


![image](images/pull_request.png)


## Reviewing a pull request

 
So you have created your first pull request, but that doesn't mean that all changes are directly onto the main branch. Commonly other Github maintainers of the repository review your new branch first before merging it. <br> Even in VCS you can get an message that someone created a pull request for an Github repository you own or are admin of.<br> This can be incredible usefull when working together on a group project.

You can find these in the Github tab and gives the following overview.<br>
![image](images/open_pull_request.png)

Once the pull request is openend you can see which files are added, removed or changed.<br>
For example this is the python code we adjusted.

![image](images/differences.png)


Inside the code is it also possible for reviewers to comment on a line of your code.<br> In this certain questions or unclearity can be asked.<br> The comment can be made to hover with your cursor on a line number, and a plus symbol should pop up.<br> Clicking on the plus symbol gives a discussion thread where you can add comments or start reviewing.<br> If this occours in your repository, which you own or manage, you will also get an email notification that this has occourd by someone else.<br> In Visual Code Studio you can also see the comments and even the response of reviewers

![image](images/commenting.png) <br><br>

![image](images/reviewing.png) <br><br>

In this phase of reviewing it's common that codes still need to be adjusted or questions have to be asked before it's approved for reviewing.<br>
When you click on description you see the total overview of the pull request and accept the request. <br>It is also possible to ask for certain reviewers

![image](images/reviewing2.png) <br><br>


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




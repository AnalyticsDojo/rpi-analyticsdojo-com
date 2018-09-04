+++
title = "Assignments"
description = ""
weight = 6
alwaysopen = true
+++

## READ THIS FIRST
For each assignment you must first *accept the assignment*.  The link to accept an assignment is not on this page but on the class page under the assignment heading. Just click on the button to accept the assignment.

Accepting the assignment will create a git repository that you will use to submit assignments. Most will be private, and they should be of the form:

```
https://github.com/techfundamentals-semester20XX/hm-xx-<your-github-username>
```



## Homework Doing Assignments on lab.analyticsdojo.com
Assignments from one class will be due the following Wednesday by 11:59 PM.  This allows for time to ask about an assignment.

These are instructions for submitting labs and assignments lab. We will be using Github Classroom to distribute and collect all assignments.  This is new for this semester so expect some bumps.

The advantage to this is that you will be learning to work with real tools while submitting assignments.

#### Step 1: Clone the private repository
- Clone the repository created when you have accepted the assignment. Just accept the assignment again (see above) if you forget or can't find it).

**Note: The command should look something like this. You will need to update it to the appropriate repository URL.***

```
git clone https://github.com/techfundamentals-fall20XX/hm-xx-<your-github-username>
```
#### Step 2: Do the assignment.
- Complete the assignment.

#### Step 3: Add your changes.
- Add your changes to the repository using the command line or GitHub Desktop.

To add all changed files via the command line, you must be in the homework directory.
```
cd hm-xx-<your-github-username>
```
Then *you must* add the files you have changed to git. The `-A` command is telling git to add all of the files. While you could name the files directly, this is the easiest way.
```
git add -A
```


#### Step 4: Commit your changes.
- Add your changes to the repository using the command line or GitHub Desktop.
```
git commit -m "insert your commit message here"
```
#### Step 5: Push your changes.
- Push your changes to the remote repository.
```
git push
```
The program should prompt you for your username and password.

#### Step 6: Verify your code.
- At the time the homework is due the final code in the repository will be tagged as the submissions and future commits won't be evaluated.  View your repository on [GitHub](https://github.com) and make sure that all of your commits have been pushed.

**I've put together a Jupyter Notebook we will use in class to go over the basics of git.  In addition, there are a number of resources posted to the [git resources tab](resources/git/). Post to the #homeworks tab on Slack.**

## Homework Doing Assignments Locally
#### Step 1: Clone the private repository
From the Github repository, click on the button *Clone or Download -> Open in Desktop*

#### Step 2: Do the assignment.
- Complete the assignment.

#### Step 3: Add and commit your changes.
Select your changed files and then enter a summary before clicking *commit to master*

#### Step 4: Push your changes.
- Push your changes to the remote repository by using the *sync* button on the top right. 
The program should prompt you for your username and password.

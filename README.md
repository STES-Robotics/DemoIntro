# DemoIntro
Made for new members for the code and management/dynamics sections of the team

**This repo is for trials on whether you have the skills to be a part of our team.**

# Rules
This repository also contains the steps to fork a repository 
<br>
Create a new branch, and push changes to the new branch.
<br>
Forking a Repository: Fork the repository onto your system by clicking the "Fork" button on the repository page.
<br>
Creating a New Branch: Create a new branch using the command git branch <new-branch-name>.
<br>
Switching to the New Branch: Switch to the new branch using the command git checkout <new-branch-name>.
<br>
Making Changes and Committing: Make changes to the code, stage the changes using git add ., and commit the changes using git commit -m "commit-message".
<br>
Pushing to the New Branch: Push the changes to the new branch using the command git push origin <new-branch-name>.
<br>
Creating a Pull Request: Create a pull request by clicking the "New pull request" button on the repository page.
<br>
<br>

# Forking a Repository and Creating a New Branch

## Step 1: Fork the Repository

<br>

Log in to your GitHub account.
Navigate to the repository you want to fork.
Click the "Fork" button in the top-right corner of the repository page.
Select the account where you want to fork the repository.
Wait for the repository to be forked.

<br>

## Step 2: Clone the Forked Repository
<br>
Navigate to your forked repository.
Click the "Code" button and copy the HTTPS URL.
Open your terminal or command prompt.
Run the command git clone <HTTPS URL> to clone the repository.
<br>
Bash
<br>

`git clone https://github.com/your-username/repository-name.git`

<br>

# Code your app/website/C code/Arduino code
<br>
<br>

## Step 3: Create a New Branch
<br>
Navigate to the cloned repository.
Run the command git branch <new-branch-name> to create a new branch.

Bash
<br>
`git branch college/your-name`
<br>


## Step 4: Switch to the New Branch
<br>
Run the command git checkout <new-branch-name> to switch to the new branch.
<br>
Bash
<br>

`git checkout college/your-name`
<br>

## Step 5: Make Changes and Commit

<br>
Make the necessary changes to the code.
Run the command git add . to stage all changes.
Run the command git commit -m "<commit-message>" to commit the changes.
Bash
<br>

`git add .`
<br>
`git commit -m "What have you created"`

<br>

## Step 6: Push to the New Branch
<br>
Run the command git push origin <new-branch-name> to push the changes to the new branch.
<br>
Bash

`git push origin college/your-name`

<br>

## Step 7: Create a Pull Request
<br>

Navigate to the repository on GitHub.
Click the "New pull request" button.
Select the new branch as the source branch.
Select the base branch (usually main or master).
Add a title and description to the pull request.
Click the "Create pull request" button.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/parkervg/DS-Progress-Journal/master)
# DS-Progress-Journal

Template for a beginner project in the UCSB Data Science Club.

Allows members to log progress in an interactive visualization using Jupyter Notebook, Pandas, Matplotlib, and mplcursors.

## Overview 

Being in an academic club like the Data Science Club is very appealing to potential employers. However, one issue with the large number of people listing "UCS Data Science Club" on their resumé is that it can be difficult to quantify the amount of progress made or knowledge gained in this extracurricular club.

This short project intends to help those motivated and driven members of the club to track their weekly progress in a matplotlib visualization, while in the process also gaining knowledge of git commands.


## Create Github Repository
We'll be using this Git Cheat Sheet to help us out. [Git Sheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)

### 1. Create GitHub account (if you haven't already) 
### 2. Link GitHub account to terminal/shell
  - In the future, we want to be able to interact with our GitHub scripts through our terminal. In order to do this, we need to point git (the programming language upon which GitHub is based on) to our account.
  - Run `git config --global user.name "Your name here"` and `git config --global user.email "Your email here"` in your terminal.
  - To ensure these config commands worked, run `git config user.name`  
### 3. Fork this repository 
  - Forking is the process of copying a repo. To do so, click the "Fork" button at the top right of this screen, next to "Watch" and "Star".
### 4. Create a local clone
  - Cloning allows us to have a local copy of all the files in the repo which we can make changes to.
  - Hit the profile button in the top right of this page. From that drop-down, select "My Repositories" and find the "DS-Progress-Journal" repo you just cloned.
  ![helpful image](https://github.com/parkervg/DS-Progress-Journal/blob/master/resources/my_profile.png)
  ![helpful image](https://github.com/parkervg/DS-Progress-Journal/blob/master/resources/your_repositories.png)
  - Copy the url of your forked repo. It should be https://github.com/YOUR_USERNAME/DS-Progress-Journal
  - In your terminal, navigate to a local directory where you want to store this project. For example, if you have a folder on your desktop called "DataScienceClub", you would type `cd desktop/DataScienceClub` for Macs, and `cd C:\Users\MyName\Desktop\DataScienceClub` for Windows.
  - Once in your desired local directory, enter `git clone https://github.com/YOUR_USERNAME/DS-Progress-Journal`. Make sure you don't just copy and paste that command and actually use your updated username.
### 5. Edit repo and push changes
  - Now, you're ready to do work in the local repo you just cloned. In the future, you're going to need to update the Github version of the repo to the version on your computer.
  - Once you've made certain changes, it's typically a 3-step process to push changes (update) the Github repo:
      1. `git add -A`                 adds all changes, deletions and insertions made to the repo locally 
      2. `git commit -m "YOUR-MESSAGE"`         adds a custom commit message where you describe the changes that have been made
      3. `git push`                 pushes all staged commits
  

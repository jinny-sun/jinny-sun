---
layout: post
title: Github Start-Up Guide
subtitle: Tips and tricks for setting up your github account
tags: [github]
comments: true
description: Are you setting up your github account for the first time? Here are some common github commands used to create a new repository, push code from your local repository to a remote respotiory, and configure your account settings.
---

## Create a New Repository
1. Create repo on GitHub
- Make sure to check “initialize this repository with a README”
- After repo has been created, click the green “clone or download” button and copy the repo web URL
2. On your local computer, go to your GitHub folder in terminal
3. Clone the repo onto your local computer: “git clone [copy repo url]”

## Track and Push Changes

1. Check displays the state of the working directory and the staging area: ``` git status ```

2. Add files to be tracked for changes and commits: ``` git add <filename> ```

3. Commit files into staging area (*Note:* Git commit will only commit files that git is tracking)

- Commit one file at a time: 
``` Git commit -m “Message here” ```

- Commit all files at once: 
``` Git commit -am “Message here” ```

4. Push files from local respository to remote repository: ``` Git push ```

5. How to configure git using anonymous git email:

- ```$ git config --global user.name "[insert your user name here]"```
- ```$ git config --global user.email "[insert your email here]"```
- If you don't want to share your personal email, follow the steps in this [link](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/setting-your-commit-email-address) on how to use an anonymous email: 



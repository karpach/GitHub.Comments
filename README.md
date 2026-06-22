# Karpach.GitHub.Comments

## Overview
GitHub Comments is Visual Studio extension with the following features:

## Features
- Enables spell checking in commit messages
- Enables adding prefix based on the git branch name
- GitHub Pull Request Comments Window - Displays all open pull requests with their comment information

![Screenshot1](Screenshots/screenshot1.png)

![Screenshot2](Screenshots/screenshot2.png)

![Screenshot5](Screenshots/screenshot5.png)

## Pro Features

### Commit message character counter

- Adds a live character counter to the Git commit message input in Visual Studio.
- The counter automatically updates as you type commit message.
- Shows the count for the **first line only** (subject line).
- Applies threshold colors:
  - Greater or equal 50 characters warning (orange-like)
  - Greate than 72 characters error (red-like)

### Atlassian Jira integration

- Adds ticket summary to the Git Changes window title
- Adds Jira button next to "Generate commit message", this button adds JIRA summary text to the commit message
  
![Screenshot3](Screenshots/screenshot3.png)  

![Screenshot3](Screenshots/screenshot4.png)  

### GitHub Comments Badge - Shows the number of pull request comments that need your reply
- Links to GitHub Pull Request Comments Window

![Screenshot5](Screenshots/screenshot6.png)

The source code is stored in the private repository, but issues can be reported in this GitHub repository.

## Installation
The extension can be installed from the [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=ViktarKarpach.KarpachGitHubComments).
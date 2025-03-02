---
layout: post
title: "  Learning about Github and how to use it"
date: 2025-03-02
author: "Andy Wang"
---
# A Brief Introduction 
In last winter vacation, I participated in an online introductory course about Git and GitHub. The
course was designed for beginners and consisted primarily of teaching videos and
interactive online practice sessions. It provided a comprehensive overview of Git's
workflow and practical guidance on how to use GitHub effectively in daily work
scenarios.This structured approach allowed me to build a clear understanding of
Git’s fundamentals and gain hands-on experience in applying its concepts.\
Course Link:\
[Getting Started with Git and GitHub - Coursera](https://www.coursera.org/learn/getting-started-with-git-and-github/home/module/1)


## Understanding Git, GitHub, GitLab and Repository

· Git: A versatile control system for tracking changes in code and collaborating with others. As a distributed version control system (DVCS), Git enables reverting to previous states,branching and merging.
· GitHub: A popular web-hosted platform for managing Git repositories,offering collaboration tools like pull requests and issue tracking.

· GitLab: A DevOps platform delivered as a single application that integrates Git repository management with CI/CD pipelines and other DevOps tools.
· Repository: A data structure for storing project files, including application source code, and tracking and maintaining version control.
· GitHub Branches: Branches in GitHub store the code in a repository . The main branch typically contains the finished and deployable version of the code, but any branch can be designed as the main. New branches can be created to modify code independently, and changes in these branches will not affect the main branch until they are merged.

## Difference between cloning and forking

· Cloning:\
1.Creates an identical copy of a remote repository on your local machine.\
2.Used when you want to work on the same project and contribute directly to the original repository.

· Forking:\
1.Creates a derivative project by copying another repository into your own GitHub account.\
2.Used when you want to make independent changes or create a personal version of a project while keeping a connection to the original (upstream) repository.

## Contribution Workflow for Forking:

1.After forking, submit a pull request to propose changes back to the original repository (upstream repo)\
2.Maintainers can review, provide feedback, or ask for conflict resolution.\
3.Merge the changes if approved.

## The roles involved in a GitHub project
 
· Developer：\
1.Communicates and collaborates with others using Git commands\
2.Focuses on contributing code and making changes to the repository.

· Integrator:\
1.Receives and reviews changes made by others\
2.Respond to pull requests and ensures changes are properly integrated.\
3.Published the merged results for others to use, often involving more advanced Git commands

· GitHub Repository Administrator:\
1.Manage the repository’s structure, organization, and interaction.\
2.Oversees community management, asset types, relationship, categories and attributes.\
3.Ensures smooth collaboration and proper governance of the repository.

## Overview of Git Workflows

· Joining an existing project:\
1.Clone the remote repository to your local machine.\
2.Create a branch and work on it.\
3.Add files to the staging area and commit them to the branch.\
4.Submit a pull request to the remote repository to merge the branch.\
5.The request will be reviewed and approved by maintainers.\
6.After merging, other developers can see the changes in the remote repository and clone it to update their local repositories.

· Starting a New project:\
1.Initialize a local Git repository.\
2.Select the files you want Git to track and move them to the staging area.\
3.Perform an initial commit to save the changes.\
4.Create a remote repository and link it to your local repository.\
5.Other developers can then clone the remote repository to their local machines for collaboration.

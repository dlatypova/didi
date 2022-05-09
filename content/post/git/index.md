---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Version control.Git."
subtitle: "Getting to know information about Version Control and Git"
summary: "Getting to know information about Version Control and Git"
authors: [Latypova Diana]
tags: []
categories: []
date: 2022-05-07T00:44:15+03:00
lastmod: 2022-05-07T00:44:15+03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: 'Image credit: [**Git**](https://analyse-innovation-solution.fr/applications/my_app/files/images/git-versionning-git-checkout-git-merge.jpg)'
  focal_point: ''
  placement: 1
  preview_only: false

authors:
  - admin


# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

**Getting to know information about Version Control and Git**

**Introduction**

In recent years, the popularity of git has shown explosive growth. This version control system is used by various open source projects. You can start by learning the most commonly used commands, and then gradually expand your knowledge. This is exactly what we will do in this article.

**What is Git?**

GIT is a distributed version control system created by Linus Torvalds to manage the development of the Linux kernel and is currently very widespread among software developers. Git has two main tasks: the first is to store information about all changes in your code, starting from the very first line, and the second is to ensure the convenience of teamwork on the code.

**What is a Version Control System?**

***The Version Control System (VCS)*** is a software to facilitate working with changing information. The version control system allows you to store multiple versions of the same document, go back to earlier versions if necessary, determine who made a change and when, and much more. Such systems are most widely used in software development for storing the source codes of the program being developed.

Version control software keeps track of all changes made to the code in a special database. If an error is detected, developers can go back and perform a comparison with earlier versions of the code to fix errors, minimizing problems for all team members.

**Centralized version control systems**

***Centralized version control systems*** are client-server applications, when the project repository exists in a single instance and is stored on the server. Access to it was carried out through a special client application.

***CVS (Concurrent Versions System, Simultaneous Versions System)*** is one of the first systems that became widespread among developers, it originated in the late 80s of the last century. Currently, this product is not being developed, this is primarily due to a number of key drawbacks, such as the inability to rename files, inefficient storage, and almost complete lack of integrity control.

***Subversion*** (SVN) is a version control system created to replace CVS. SVN was developed in 2004 and is still in use. Despite many advantages over CVS, SVN still has disadvantages, such as problems with renaming, inability to delete data from storage, problems in the branch merge operation, etc. In general, SVN was (and remains) a significant step forward compared to CVS.

**Distributed version control systems**

***Distributed Version Control Systems*** (DVCS) allow you to store a repository (a copy of it) for each developer working with this system. At the same time, it is possible to allocate a central repository (conditionally) to which changes from local ones will be sent and, with it, these local repositories will be synchronized. When working with such a system, users periodically synchronize their local repositories with the central one and work directly with their local copy. After making a sufficient number of changes to the local copy, they (changes) are sent to the server. At the same time, the server is most often chosen conditionally, since in most DVCS there is no such thing as a “dedicated server with a central repository".

**Git hosting**

A number of services provide hosting for git repositories, among the most famous are GitHub, Codebase, SourceForge, SourceHut, Gitea, Bitbucket, GitLab.

**What is an SSH key and why is it needed?**

To work from your computer with GitHub, to have access to projects stored on the service, to execute commands in the console without constantly confirming the password, you need to log in with the server. SSH keys help with this.
Each SSH key contains a pair: a public (public) and a private (private) key. The public key is sent to the server, you don't have to hide it from everyone and not worry that someone will see it and steal it. It is useless without its private key pair. But the private key is the secret part. Only you should have access to it.

**Basic git commands**

The **git add** command adds the contents of the working directory to the index (staging area) for a subsequent commit.

The **git status** command shows the status of files in the working directory and index: which files have been modified but not added to the index; which are waiting for a commit in the index.

The **git diff** command is used to calculate the difference between any two Git trees.

The **git commit** command takes all the data added to the index using git add and stores their cast in the internal database, and then shifts the pointer of the current branch to this cast.

The **git rm** command is used in Git to delete files from the index and working copy.

The **git mv** command is just a convenient way to move a file and then execute git add for the new file and git rm for the old one.

The **git clean** command is used to remove garbage from the working directory.

**Conclusion**

We have analyzed the basic knowledge of what a Version Control System and Git are. I tried to collect all the most important information and present it as succinctly and concisely as possible. Git is quite complex, and there are many more functions in it...
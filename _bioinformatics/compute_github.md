---
title: GitHub
last_modified_at: 2018-06-20
---
While version control software has evolved over time, a new evolution that is happening more and more is the need for a wider group of researchers to actively use version control resources to manage their code and documentation of processes that are ongoing in their research.  From the perspective of reproducibility, share-ability and interoperability, the need for a sharing platform that integrates version control and collaboration is becoming more and more a critical part of a researcher's toolkit.  Thus, regardless of the degree to which code plays a direct role in a research project, more and more often at least a cursory understanding of what GitHub is and how it can be utilized in scientific research is important.  

## What is Github?
GitHub at it's core is a Git repository hosting service.  While Git is a command line tool, GitHub provides a Web-based graphical interface as well as access control and several collaboration features, such as wiki's and basic task management tools for projects.  GitHub is a free service that individuals can make their own usernames to join the service and begin hosting publicly accessible repositories containing code they have produced or edited.  As GitHub was originally intended to facilitate open source software development, the basic resources available to users are only public, but free, repositories in order to continue to encourage developers to keep their code in the open and shared.  There are a wide variety of ever-changing features that GitHub provides that facilitates code sharing, communication, version control, project management, and software development tools such as facilitating software release and documentation.  

### Command Line Git
The original command-line tool, git is the only place you can run all Git commands — most of the GUIs implement only a partial subset of git functionality for simplicity. If you tend to do the majority of your work via the command line, the logical way to interact with git and version control is likely via the command line version of Git.  Access to the command line version of Git is through Terminal in Mac or Command Prompt or Powershell in Windows.  To read more about command line [Git, follow this link.](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)  To download a version of git to your local machine, [follow this link.](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

### GitHub Desktop Client
For many users, command line git is not the ideal mode of interacting with version control software.  As an example, if the majority of the code produced by a user is originating from interfaces such as RStudio, it may be much simpler and more straightforward to use GitHub via the desktop client.  You can download the desktop client for your system for free [here.](https://desktop.github.com/)

The desktop client will allow you to "clone" repositories from the web based GitHub source and allow you to work on those files locally.  Then when edits have been made to files in those repositories, those edits will be shown in the GitHub Desktop client for the user to then comment on and commit those changes to the version of the repository on the web.
![]({{ site.baseurl }}/compdemos/assets/comp_github-96005f6a.png)

There are many different ways of working with multiple people on multiple files in a GitHub repository, and there are many places on the web that can provide some insight into how to use it's many features.  However, [this GitHub Guide for the flow of using GitHub is useful for understanding the basics.](https://guides.github.com/introduction/flow/)
![]({{ site.baseurl }}/compdemos/assets/comp_github-5c26f4cd.png)

### Git Kraken
More to come on [Git Kraken](https://www.gitkraken.com/) as a Desktop client option is to come, but to summarize, it is another desktop application that runs more consistently on Mac, PC, and Linux, and allows for greater control and granularity than GitHub Desktop.  It is good for advanced beginners and beyond.    

## Sharing with GitHub
Given the history of GitHub being linked with open source software development, it is set up with the intention to prioritize publicly accessible code.   However, given the need to limit access to code under development and not ready for public input, or other situations such as in the context of biomedical research, private repositories are available.  

### Public vs Private Repositories
When creating a repository the user chooses whether it should be public or private.  Private repositories require payment, but GitHub provides unlimited, free public repositories.  

### Individual vs Institution GitHub Repositories
When the software is being developed as part of an institution, such as at Fred Hutch, users can use repositories that are their individual repositories OR their username can be associated with an institution.  The Fred Hutch supports the use of GitHub for research via this institutional account which allows all Fred Hutch employees to create public *or* private repositories.  This wiki itself is developed and managed via a Fred Hutch institution [GitHub repository.](https://github.com/FredHutch/wiki)  This resource is a valuable tool for researchers looking to manage, communicate and document code or analysis processes in a platform that can be both private or public, and where they can manage permissions to their repositories.

### GitHub API
More to come about using the GitHub API

## Available Resources and links
There a wide variety of resources on the web for learning to use the various forms of GitHub.  
- Get a [GitHub username here.](https://github.com/join)
- Join the Fred Hutch GitHub institution by sending your username to `helpdesk` and request to be added.  
- Getting started with [GitHub Desktop](https://help.github.com/desktop/guides/getting-started-with-github-desktop/)
- How to [contribute to projects with GitHub](https://help.github.com/desktop/guides/contributing-to-projects/)
- A good tutorial slide deck on how to use GitHub with command line can be found [here](https://s3-us-west-2.amazonaws.com/fredhutch-docs/Introducing-Git-and-GitHub.pdf).
  - Signing up for a GitHub account - Slide 12
  - How to be part of Fred Hutch GitHub Organization - Slide 13
  - Creating a new GitHub Repo - Slide 14
  - Cloning repository (repo) to local machine - Slide 19
  - Keep your local repo up to date, in the scenario of collaboration with others or moving to a different machine. - Slide 21
  - Make change to files locally and commit the changes - Slide 23 ~ 27
  - Push the local committed changes to the remote GitHub repo - Slide 28
  - Collaborations internally and externally - Slide 31 ~ 43

---
title: Concepts
description: ''
position: 20
category: GitHub
---

## Terminology

### GitHub
GitHub is a code hosting platform for version control and collaboration.

Some Standards organizations they use it also to create technical documents, white papers, code, etc
In these guidelines, we used Flavored Markdown as a text format to build documents.

This text has a special formatting syntax that is understood by GitHub and renders it in the browser as rich text.

<alert>
Outside of GitHub, the markdown content may or may not render correctly.
</alert>

### Repository (repo)
A directory or storage space where the projects are safely kept. Sometimes, we call it a `repo`, as an abbreviated word.

### Branches
The content in a repo is organized in `branches` (like a folder in an FTP).

Only roles with write access, such as Chairs, Editors or Maintainers can create branches. Regularly, branches are merged into each other.

### Commit
It is a way to identify changes to one or more files in a branch. Each commit is identified by a UNIQUE ID or hash.

### Pull Request
It is a way to group commits on GitHub. 
It allows people to review your changes = commits in a single place.

In GitHub, each pull request contains all the changes and comments provided by people during the discussion.

### Issues
It is a way to track ideas, enhancements, tasks, bugs, action items, collect feedback, etc.
It is possible to use labels to qualify the type of issue.

## Repository Home Page

<img width="699" alt="image" src="https://user-images.githubusercontent.com/3258579/182497904-8c11da1a-9f8d-4a94-b6c2-3451cd50ca7b.png">

### Watch
It is used to register to receive or stop notifications via email.

### Star
It indicates that you like and follow up on this repository (repo).

### Fork
To copy this repo content into your personal GitHub account.

### Code
This is the area where the content in the repository (code, text) is stored.

### Issues
It is used to provide feedback, comments, etc.

### Pull Request
By clicking this link you will open a page containing all the open and close Pull Requests, which contain changes to documents and exchange of comments between participants.

### Projects
It is a Kanban type of billboard. It is used to move Issues and Pull Requests from column to column. 

### Branches in the repo
A branch contains a unique set of text files and it is provided with a name. Each repository can have one or multiple branches. Branches can be merged one into another. 

### Add file
This function allows creating a file a file from scratch using the web browser. Please note that uploading files are only available for those members that have WRITE access to the repository.

### Code
When clicking on this button, it is possible to download the document on the related branch or copy the URL to clone the repository.

### Security
In GitHub people are organized in Teams, and then Teams are allocated to repositories (repos).

When a Team is allocated to a repo, the administrator indicates what access rights are given to the people in the Team. Each Team receives a name. You can create as many Teams as you need.

These are the typical roles assigned to a repository and its access rights:
#### Members
* TRIAGE: 
  * Can read and clone a repository. 
  * Can also manage issues and pull requests

#### Chairs, Editors, Maintainers
* WRITE:
  * Can read and clone and push to a repository (direct changes without creating a pull request)
  * Can also manage issues and pull requests

### Fork
It is an action that copies a repository from e.g., OMP to your personal GitHub account.
A FORK operation is performed by clicking the "Fork" button.

<img width="418" alt="image" src="https://user-images.githubusercontent.com/3258579/182501211-3ec3a208-ebda-439d-91e5-90032ec0d64a.png">

### Clone
It is an action executed via the Git command line, where a repository is copied to your working directory (in your laptop)

e.g., of a clone git command:

```git
  $ git clone https://github.com/OpenManufacturingPlatform/omp-training-repository-private.git
```

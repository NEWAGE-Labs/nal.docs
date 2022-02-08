# Standard Operating Procedure - GitHub

>Most recently edited by: *Paul VanderWeele*  
>Most recent edit date: *Feb 8th, 2022*  
>Edits were authorized by:  

## Table of Contents

[Related Procedures](#related-procedures)  
[Purpose and Scope](#purpose-and-scope)  
[Terms and Definitions](#terms-and-definitions)  
[Training](#training)

## Related Procedures

##### Pre-Requisites Procedures  

[QSP - Document Control](../../QSPs/Document Control and Management.md)  
[Workstations](./Workstations.md)  
[Web Browsers](./Web Browsers.md)  
[Git](./Git.md)  

##### Other Related Procedures  

[Markdown](./Markdown.md)  
[Interpersonal Communication](./Interpersonal Communication.md)  

## Purpose and Scope

The purpose of this procedure is to explain the functionality and process flow of using [GitHub.com](https://www.github.com) to manage documents in a controlled manner using [Git](./Git.md) as a foundational mechanism. It includes both an introduction for NEW AGE personnel, as well as references to the official 3rd party documentation for the web service.

This procedure is NOT an alternative for the [Git](./Git.md) procedure, but rather is an extension to using the *Git* tool. Git is open source, and is used as a version control system; while GitHub is a [Web Application](#web-application) hosted by Microsoft used for collaboration and project management.

## Terms and Definitions

##### User  

> A GitHub User is an entity controlled by 1 personnel, and is used to manage, create, and contribute to repositories on GitHub.com.

##### Organization

> A GitHub Organization is an entity controlled by 1 or more personnel, and is used to organize projects that are contributed to by multiple users. The Organization for NAL is [NEWAGE-Labs](https://github.com/NEWAGE-Labs).

##### Web Application

> A Web Application is a software program that runs on a computer open to internet traffic. Users connect to the web application via a [web browser](./Web Browsers.md), via http/ssh on [BASH](./BASH.md), or via the [Atom](./Atom.md) text editor.

##### Pull Request

> A Pull Request is a GitHub-specific operation to help organize discussions around a particular set of commits BEFORE the commits are merged into the primary branch. This is the primary feature of using GitHub rather than simply using a local Git repository.

>Sometimes a pull request is for one user to `git-pull` a branch from one repository to another, but it is often used inside a single repository to add commentary on a feature update before it is merged. Pull Requests have a Open/Closed state that can be toggled, and can also reference [Issues](#issue).

##### Merge

> A Merge on GitHub is slightly different than a raw `git-merge`, but uses the same machinery underneath. A GitHub Merge is an operation on a [Pull Request](#pull-request) that merges all staged commits in the request.  

> A Merge can contain additional commentary about issues and corrective actions relating to software release process itself, or relevant hotfixes following the merge.  

##### Repository

> A Repository on GitHub is essentially the same as a `repo` in [Git](./Git.md), but is formatted to functionally interact with the rest of the GitHub application.  

##### Commit

> A Commit on GitHub is essentially the same as a `commit` in [Git](./Git.md), but is formatted to functionally interact with the rest of the GitHub application.

##### Author

> An Author on GitHub is a User who is specifically responsible for the upload or editing of a commit or [Pull Request](#pull-request).

##### Reviewer

> A Reviewer on GitHub is a [User](#user) who is requested for reviewing commit changes in a [Pull Request](#pull-request).

##### Assignee

> An assignee on Github is a [User](#user) who is assigned to a particular [Issue](#issue) or [Pull Request](#pull-request).

##### Project

> A Project on GitHub is a collection of [Issues](#issue) for either a specific [Organization](#organization), or a specific [Repository](#repository).

##### Issue

##### Milestone

##### Label

## Training

The `Hello World` [Quickstart Guide](https://docs.github.com/en/get-started/quickstart/hello-world) the primary part of training for NEW AGE personnel who utilize GitHub, and completion of it is sufficient to obtain competency. Alternative repository work can be used as evidence for competency if it contains each component of the branch-commit-pull-merge process.

Personnel must successful complete the guide (or other sufficient work) on the GitHub account that is marked as a contributor to the [NEWAGE-Labs GitHub Organization](https://github.com/NEWAGE-Labs).

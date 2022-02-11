# Standard Operating Procedure - GitHub

>Most recently edited by: *Paul VanderWeele*  
>Most recent edit date: *Feb 11, 2022*  
>Edits were authorized by: *Paul VanderWeele*  

## Table of Contents

[Related Procedures](#related-procedures)  
[Purpose and Scope](#purpose-and-scope)  
[Terms and Definitions](#terms-and-definitions)  
[Training and Authorization](#training-and-authorization)  
[Additional Information](#additional-information)  

## Related Procedures

##### Pre-Requisites Procedures  

[QSP - Document Control](../../QSPs/Document Control and Management.md)  
[Workstations](./Workstations.md)  
[Web Browsers](./Web Browsers.md)  
[Git](./Git.md)  

##### Other Related Procedures  

[Markdown](./Markdown.md)  
[Interpersonnel Communication](../Personnel/Interpersonnel Communication.md)  

## Purpose and Scope

The purpose of this procedure is to explain the functionality and process flow of using [GitHub.com](https://www.github.com) to manage documents in a controlled manner using [Git](./Git.md) as a foundational mechanism. It includes both an introduction for NEW AGE personnel, as well as references to the official 3rd party documentation for the web service.

This procedure is NOT an alternative for the [Git](./Git.md) procedure, but rather is an extension to using the *Git* tool. Git is open source, and is used as a version control system; while GitHub is a [Web Application](#web-application) hosted by Microsoft used for collaboration and project management.

## Terms and Definitions

##### User  

> A GitHub User is an entity controlled by 1 personnel, and is used to manage, create, and contribute to [Repositories](#repository) on [GitHub.com](https://github.com). User actions can be considered uniquely performed by a single personnel, and can therefore be used as a signature for [Technical Records](../../QSPs/Technical Records.md).

##### Organization

> A GitHub Organization is an entity controlled by 1 or more personnel, and is used to organize projects that are contributed to by multiple users. The Organization for NAL is [NEWAGE-Labs](https://github.com/NEWAGE-Labs, and is a major component of the [NAL Document Control System](../../index.md/#83-control-of-management-system-documents-option-a).

##### Web Application

> A Web Application is a software program that runs on a computer open to internet traffic. Users connect to the web application via a [web browser](./Web Browsers.md), via http/ssh on [BASH](./BASH.md), or (in the case of GitHub) via the [Atom](./Atom.md) text editor.

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

> An assignee on GitHub is a [User](#user) who is assigned to a particular [Issue](#issue) or [Pull Request](#pull-request).

##### Project

> A Project is an entity on GitHub that is a collection of [Tasks](#task) for either a specific [Organization](#organization), or a specific [Repository](#repository).

##### Task

> A Task in an entity on GitHub inside of a [Project](#project). Tasks are often are linked 1-to-1 with [Issues](#issue) to create project management structure across various [Repositories](#repository).

##### Issue

> An issue is an entity on GitHub, typically pertaining to a proposed change or current problem with a [Repository](#repository) or to an [Organization](#organization). Issues are often linked 1-to-1 inside of a [Project](#project) with [Tasks](#task), and can be expanded by linking additional entities like [Authors](#author), [Reviewers](#reviewer), [Assigness](#assignee), [Pull Requests](#pull-request), [Milestones](#milestone), and [Labels](#label).

> Issues are the primary place of recorded conversation and collaboration on GitHub for both NAL software development and NAL quality management document control. Issues are part of the NAL [Technical Records](../../QSPs/Technical Records.md).

##### Milestone

> A Milestone is an entity on GitHub that denotes deadline for a collection of [Issues](#issue). Milestones can be used to help organize [Projects](#project) around important deadlines and company goals.

##### Label

> A Label is an entity on GitHub that can be applied to [Issues](#issue) to help index and organize them. Multiple Labels can be used to create sub-lists and to aid in documentation.

## Training and Authorization

The `Hello World` [Quickstart Guide](https://docs.github.com/en/get-started/quickstart/hello-world) is the primary part of training for NEW AGE personnel who utilize GitHub, and completion of it is sufficient to obtain competency to contribute to repositories in the organization. Alternative repository work can be used as evidence for competency to contribute to repositories if it contains each component of the branch-commit-pull-merge process.

Publishing of documents to the NAL Organization's GitHub Pages sites is considered a separate training, and sufficient evidence of competency can be attained by completing the [Quickstart](https://docs.github.com/en/pages/quickstart) and [Getting Started](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages) guides on the [GitHub Pages Documentation](https://docs.github.com/en/pages) site, or by showing evidence of competency for [MkDocs](./MkDocs.md).

Personnel must successfully complete all guides (or other sufficient work) on the GitHub account that is marked as a contributor to the [NEWAGE-Labs GitHub Organization](https://github.com/NEWAGE-Labs). The supervisor(s) for the training is the User marked as ***Owner*** of the NAL organization.

## Additional Information

Additional information, resources, and up-to-date trainings can be found in the [Official GitHub Documentation](https://docs.github.com/en).

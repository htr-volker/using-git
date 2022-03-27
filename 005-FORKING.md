# Forking

## Overview

**Forking** is a tool that is provided by repository-hosting services (such as GitHub and GitLab) that allows users to create copies of public repositories under their own accounts.

This repository is then independent from the original, giving the user full reign to modify the code without impacting the original code.

The forked repository is still linked to the original repository, which allows new changes from the original to be merged into the forked repository after it is copied *and* allows changes to the forked repository to be integrated into the original.

As a result, forking is a valuable tool for contributing to public open-source projects.

## Forking

Developers are able to collaborate on projects by cloning repositories to their local machines and pushing/pulling changes to/from the *origin*.

When hosting your *origin* repository on a repository-hosting service such as GitHub, only authorised users are allowed to push new changes to the *origin*. They can be added to the project as *contributors* by the owner(s) of the project.

However, repo-hosting sites such as GitHub provide a way for developers to contribute to the code *without* needing to be added to the original project as an official contributor.

**Forking** is the process of taking a Git repository that is owned by one user and making a copy of it (including all files *and* the full commit history of all branches) under another user's account.

Once a repo has been forked, the forker has full access to the code and can make any changes to it *without making changes to the original*. They effectively have a version of the code that they have full reign to modify however they would like.

### Contributing to a Forked Repository

It is common for developers to fix bugs or suggest new features to public projects on GitHub by forking the repository. When they have made their improvements on their forked repo, they may propose that the changes be integrated into the original repository.

We refer to the original repository in this instance as the *upstream* remote. The term *upstream* is simply a reference to the original repository's URL, but is distinguished from the *origin* in that it is under somebody else's GitHub account.

To propose that the changes from the forked repository be integrated into the *upstream*, the forker can stage a *Pull Request (PR)* (also regularly known as a *Merge Request*) on GitHub.

The Pull Request will appear on the original repository's page, allowing owners and contributors for the original repository to review the code, provide comments and suggestions and ultimately decide whether to accept or decline the PR.

### Updating from a Forked Repository

As the forked repository and the original repository are still linked, new changes made to the original repository can be easily pulled into the forked one.


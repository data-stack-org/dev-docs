# Git flow

We use simple [git-flow](http://nvie.com/posts/a-successful-git-branching-model/). You can find down a short description of the flow.

## Branches

Instead of a single master branch, this workflow uses two branches to record the history of the project: `master` and `development`. The master branch stores the official release history, and the develop branch serves as an integration branch for features.

## Feature implementation

While working on a task, make sure that you follow these rules:

* New feature (`bugfix`, `hotfix`, etc) branch is created from a `develop` branch;
* Branch name is the same as feature name and has `feature/` prefix. For example, branch for *"Add navigation sidebar"* feature will be named as `feature/add-navigation-sidebar`;
* One feature can have only one branch related to it;
* Assign stakeholders to the Pull request.

## Pull request

All commits should contain descriptive messages. Messages like `hotfix`, `fix`, `bugfix`, etc not acceptable.

**Branch naming example:**

```
feature/provide-project-modal
hotfix/display-notification-on-error
```

**Not:**

```
hotfix
feature/modal
```

As soon as your job is done - you can make a pull request.

How to ensure that your code is ready for review:

* It is stable (no failures, no simple/stupid bugs);
* It meets requirements of your task;
* All linters (PEP, FLAKE, ESLINT, SASSLINT, etc.) and tests passed.

When you create a new pull request, add at least 3 team stakeholders as reviewers.

## Code review

How to review:

* If you have any comments write them and press `Request changes`;
* When all comments were fixed or you do not have any questions or fix notes, mark PR as `Approve`;
* When PR has 3 approves and there are no requested changes, then it can be merged by stakeholder.

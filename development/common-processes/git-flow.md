# Git flow

We use simple [git-flow](http://nvie.com/posts/a-successful-git-branching-model/). You can find down a short description of the flow.

## Branches

Instead of a single master branch, this workflow uses two branches to record the history of the project. The master branch stores the official release history, and the develop branch serves as an integration branch for features.

## Feature implementation

For every task developer makes, he must to:

* Create feature branch from a `develop` branch
* Branch name is equal to the feature name, but has `feature/` prefix;
* One branch is equal to only one feature;
* Assign stakeholders to the pull-request.

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
* All linters(PEP, FLAKE, ESLINT, SASSLINT, etc.) and tests passed.

When you create a new pull request, add at least 3 team stakeholders as reviewers.

## Code review

How to review:

* If you have any comments write them and press `Request changes`;
* When all comments were fixed or you do not have any questions or fix notes, mark PR as `Approve`;
* When PR has 3 approves and there are no requested changes, then it can be merged by stakeholder.

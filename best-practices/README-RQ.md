# Best practices

## Creating a Feature Branch

Feature branches (or sometimes called topic branches) are used to develop new features for the upcoming or a distant future release. When starting development of a feature, the target release in which this feature will be incorporated may well be unknown at that point. The essence of a feature branch is that it exists as long as the feature is in development, but will eventually be merged back into develop (to definitely add the new feature to the upcoming release) or discarded (in case of a disappointing experiment).


When starting work on a new feature, branch off from the **develop** branch.

* Switched to a new branch "myfeature"

> $ git checkout -b myfeature develop




For more reference for the Branches take a look in this  article
[Git branching model](http://nvie.com/posts/a-successful-git-branching-model/)

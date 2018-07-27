I will try and follow this development model. 
https://nvie.com/posts/a-successful-git-branching-model/

To create a new feature branch
git checkout -b myfeature develop

To merge this branch with the develop branch
$ git checkout develop
Switched to branch 'develop'
$ git merge --no-ff myfeature
Updating ea1b82a..05e9557
(Summary of changes)
$ git branch -d myfeature
Deleted branch myfeature (was 05e9557).
$ git push origin develop

For details on how to use git and eclipse, see here 
http://wiki.eclipse.org/EGit/User_Guide#Recording_Changes_in_the_Repository

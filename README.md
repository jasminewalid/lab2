how to delete a branch locally:
you can use : git branch -d :
to delete a local branch that has not been fully merged : git branch -D :

how to delete a branch remotely:
To completely remove a remote branch, you need to use the git push origin command with a -d flag, then specify the name of the remote branch.

![Screenshot from 2023-11-27 13-01-50](https://github.com/jasminewalid/lab2/assets/152063571/e5e11a39-acef-4fc2-b6e8-f7d582849581)

![Screenshot from 2023-11-27 13-05-29](https://github.com/jasminewalid/lab2/assets/152063571/9149f6a6-171e-400a-b60e-2bff689a5c3c)

how to list tags:
you can use : List tag
or : git tag

how to delete a tag locally:
you can use : git tag -d

to deletet a tag remotely:
you can use : git push remote-name --delete tag-name

![Screenshot from 2023-11-27 13-56-32](https://github.com/jasminewalid/lab2/assets/152063571/230b9d85-c1ae-4eea-91ce-6abd03103235)

![Screenshot from 2023-11-27 14-09-00](https://github.com/jasminewalid/lab2/assets/152063571/7b9bc9a6-3bff-4da7-b35d-dea3ebf96e10)

git rebase example
![git-rebase-cover](https://github.com/jasminewalid/lab2/assets/152063571/aa29e6a4-853c-47b1-a722-ea2c04eb51c1)

What is a pull request in GIT ?
A pull request, often abbreviated as PR, serves as a proposal to merge changes
made in one branch of a repository into another, typically from a feature branch into
the main branch. Pull requests are essential for facilitating code reviews,
encouraging collaboration, and maintaining a clean, well-documented codebase.
Pull Request Examples
● Feature Additions: A developer adds a new feature, like password reset, and
creates a pull request to merge it into the main branch after approval.
● Bug Fixes: A separate branch is made to fix a discovered bug, and a pull
request is created for team review and integration.
● Code Refactoring: Developers refactor code for better performance or
readability and submit a pull request for team approval.
● Dependency Updates: After reviewing for compatibility and improvements, a
pull request updates the project’s dependencies to the latest versions.
How to create a pull request?
If you have changes ready to submit for approval on GitKraken Client, you can
drag-and-drop your feature branch onto the target branch of the main repo to trigger
the “Create a pull request” option from the drop down menu.
You can also initiate this process by clicking the green + icon on the Pull
Requests section on the left panel.
To complete the process of creating your PR, simply hit Create pull request at the
bottom of the Git pull request template

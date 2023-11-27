how to delete a branch locally:
you can use git branch -d :
git branch -d branch-to-delete.
but to delete a local branch that has not been fully merged (i.e. force delete), you must use git branch -D :
git branch -D branch-to-delete.

how to delete a branch remotely:
To completely remove a remote branch, you need to use the git push origin command with a -d flag, then specify the name of the remote branch.

![Screenshot from 2023-11-27 13-01-50](https://github.com/jasminewalid/lab2/assets/152063571/e5e11a39-acef-4fc2-b6e8-f7d582849581)

![Screenshot from 2023-11-27 13-05-29](https://github.com/jasminewalid/lab2/assets/152063571/9149f6a6-171e-400a-b60e-2bff689a5c3c)

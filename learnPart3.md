### Learning how to create branch

 Creating branch helps us to create copy of the whole repository without affecting the original files. 
 Branching helps to maintain original files and track the changes easily, so in the process of editing we do not 
 loose the original version.To create a branch:
1. Type `git branch ...`. + `Enter`. Here,"..." write the name of the branch you want. Let's say demobranch.
2. To check the active branch type `git branch`. It will list all the branches available in the repository.
3. In order to work in the specified branch, type `git checkout demobranch` + `Enter`. 
 Now you can work easily on the files and make changes. And add, commit the changes.
4. In order to push the changes, type `git push --set-upstream origin demobranch`

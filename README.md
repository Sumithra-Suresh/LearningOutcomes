# LearningOutcomes

## Git

### Why do we use Git?
Git is a version control software used to keep track of the changes made it to the files. It will give an option to revert back to any versions at anytime.

### What’s the difference between Git and GitHub?
Git is local repository and GitHub is a cloud based remote repository that will help us to manage the git repositories.
We will work on the local repos using Git and push it to the remote GitHub repository. 

### What happens when you clone a repository?
Clone will make a copy of the remote repository to the local repo.

### What happens when we do git pull origin main
 'git pull origin main' will pull all the changes from the remote repo and update the local repo. 

### How do we create a new branch on our local machine?
We can create a new branch using the following command : git checkout -b <branch-name>

### How do we control which changes will be included in the next commit?
We can use git add . to include the changes in the next commit.

git add . is inappropriate if we dont want to include all the modified files to the specific commit.

Before commit, we need to make sure the local repo matches with the remote repo by pulling all the changes from the remote repo. By this way we can avoid conflicts with the main.

 
git push origin [branch-name] will push the local changes to the GitHub repo.

PRs help us to review the proposed changes with the teammates before merging the changes to the project.

We need to review the teammates PRs to make sure the proposed changes are inlined with the related issues.


## HTML

Accessibility is important, because it will make sure the application is accessible to as many people as possible. Specifically for those with special needs.

We can find the simple accessibilty problems using chrome developer tools, LightHouse.


Sematic HTML element clearly describes its meaning to both the browser and the developer.

 Using the correct semantic element will greatly improve the accessibility.

<form> element provides an interactive controls for submitting information.


## CSS

We can define all the color variables inside <element :root> and use it using var().

Flexbox is a one dimensional layout method used for arranging items in either row or column. We can specify the direction using flex-direction property.

Resopnsive design is important to make sure the application is presentable across all screen resolutions and sizes.

## JS
var should be avoided because of scoping, hoisting and redeclaration.

We can make a long, complex chunk of code easier to read by breaking them into smaller functions.

Callback is a function passed as an argument to another function, to be "called back" at a later time.

## Array Methods

array.map(callback) - callback is applied to every element of the array and the new array will be returned.

array.filter(callback) -  callback is applied to all element and filters the element which are false. 

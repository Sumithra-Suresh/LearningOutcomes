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

### When might git add . be inappropriate?
Git add . is inappropriate if we dont want to include all the modified files to the specific commit.

### How do we make sure our local changes don’t conflict with main ?
Before commit, we need to make sure the local repo matches with the remote repo by pulling all the changes from the remote repo. By this way we can avoid conflicts with the main.

### What does git push origin [branch-name] do?
git push origin [branch-name] will push the local changes to the GitHub repo.

### Why do we make pull requests instead of just changing main directly?
PRs help us to review the proposed changes with the teammates before merging the changes to the project.

### Why should you review your teammates’ pull requests?
We need to review the teammates PRs to make sure the proposed changes are inlined with the related issues.


## HTML

### Why is accessibility important?
Accessibility is important, because it will make sure the application is accessible to as many people as possible. Specifically for those with special needs.

### How can you quickly find simple accessibility problems?
We can find the simple accessibilty problems using chrome developer tools, LightHouse.

### What is semantic HTML?
Sematic HTML element clearly describes its meaning to both the browser and the developer.

### Why is it important to use the “correct” semantic element?
 Using the correct semantic element will greatly improve the accessibility.

### What is the <form> element used for?
<form> element provides an interactive controls for submitting information.

## CSS

### How would you use CSS variables to make a reusable colour palette?
We can define all the color variables inside <element :root> and use it using var().

### How would you use flexbox to make elements sit on a single line?
Flexbox is a one dimensional layout method used for arranging items in either row or column. We can specify the direction using flex-direction property.

### How would you use grid to make a layout that automatically adds columns as the screen gets wider?
ToDo

### Why is it important to create a responsive design?
Resopnsive design is important to make sure the application is presentable across all screen resolutions and sizes.

### How would you structure your CSS to make it “mobile-first”?
ToDo

## Javascript

### Why should we avoid using var to define variables?
var should be avoided because of scoping, hoisting and redeclaration.

### How might you make a long, complex chunk of code easier to read?
We can make a long, complex chunk of code easier to read by breaking them into smaller functions.

### What is a “callback”?
Callback is a function passed as an argument to another function, to be "called back" at a later time.

## Array Methods

### How would you use array.map() to create a new array with transformed values?
array.map(callback) - callback is applied to every element of the array and the new array will be returned.

### How would you use array.filter() to create a new array with certain values removed?
array.filter(callback) -  callback is applied to all element of an array and filters the elements which are failed to meet the conditions given in the callback. 

### How would you use array.find() to get a single value from an array?
find() will return the first element that satisfies the condtion passed in the find().

## Promises & fetch 

### What is a promise?
Promise is an object returned by an asynnchronous functions.

### How do promises help manage asynchronous code?
Promises got predefined handlers to handle the response of an asynchronous functions.

### What does a promise’s .then method return?
Promise's .then() method will returns a promise.

### How could you chain promises together to avoid “callback hell”?
Below is an example to use promises chain to avoid "callback hell" : 
<code>
fetch("url")
.then()
.then()
.catch();
</code>

### How would you handle a fetch request that failed to get a response from the server?
We can handle the failed fetch request using catch() handler.

### How would you handle a fetch request that received a 404 response from the server?
404 response should be handled by the then() handler. It will be reported by response.status key. 

## HTTP

### What is an HTTP request?
HTTP request is made by the client to the server to access the resources stored in the server.

### What kind of request is sent when you click a link in your browser?
GET request is sent when you click a link in the browser.

### What kind of request is sent when you submit a form in your browser?
POST request is sent when you submit a form in the browser.

### What is an HTTP response?
HTTP response is sent by the server to the client for the HTTP request made by the client.

### What does the status code of an HTTP response tell us?
The status code tells us whether the request is success or failed.

### What are some common status codes?
200-299 - successfull response
400-499 - Client error

### What are HTTP methods for?
HTTP methods tells the kind of action needed for that request.

### What kind of request should have a GET method?
GET will get the data from the server.

### What kind of request should have a POST method?
POST will send information to the server.

### What kind of request should have a PUT method?
PUT will replace the target content with the source content.

### What kind of request should have a DELETE method?
DELETE will delete the specified target content.

### What is the “body” of an HTTP request for?
HTTP request body is the data sent by the client to the server.

### What is the “body” of an HTTP response for?
HTTP response body contains the requested data send by the server to the client. 

## DOM

### How would you get a reference to a DOM element in your JS?
We can get a reference to a DOM element in JS file using getElementBy or QuerySelector().

### How would you get references to multiple DOM elements at once in your JS?
Using querySelectorAll()

### How would you update properties of a DOM element?
We can update the dom element by using innerHTML, Textxcontent or innertext.

### What’s the difference between a “property” and an “attribute”?
ToDo

### What are some different ways to add content inside a DOM element?
By using createElement and appendChild.

### When might the <template> element be useful?
 ToDo
 
### What are the different ways to add event handlers to elements?
We can use element.addEventListener() or we can use element attribute in the html file.

### Why is addEventListener the safest way to add an event handler?
Using addEventListener we can add multiple event handler to the same element.

### How can you access submitted form values in your JS?
Using the DOM element references or using FormData.

## Testing

### Why are tests useful?
Tests are useful to prevent bugs.

### What is the difference between unit and integration tests?
Unit testing are used to test a small block of code. Integration testing are used to test multiple block of codes.

### What kind of code is easier to test?
The code block with predefined input and predefined outputs are easier to test.

### Why should your tests be isolated from each other?
Tests should be isolated from each other so it will be easy to find bugs.

### What is Test Driven Development (TDD)?
TDD is a practice to write the test cases for small block of code before start coding.

### When might TDD be a useful process to follow?
TDD is a useful process to follow if we have predefined input and output.

## Debugging

### What process would you take to find out why your code isn’t working?
Using console.log().

### What tools do JS/dev tools have to help debug your code?
There are various dev tools to help debug the code like breakpoints, watch expression etc. But so fae I have used only console panel to debug the code.

### At what point should you ask for someone else’s help?
We have to seek for someone's help, if we are not able to locate the problem or spending too much time or struggling to find better solution.

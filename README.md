# QuickSnippets

QuickSnippets is a VS Code snippet extension which helps developers in writing code with ease and provides snippets for boilerplate code.

## Features
The extension currently supports JavaScript language and other libraries based on it like express and mongoose.

## Requirements
VS Code

## How to Use

### Axios

| Command | Description |
| ---- | ---- |
| axiosGET | GET request using Axios |
| axiosPOST | POST request using Axios |
| axiosPUT | PUT request using Axios |
| axiosDELETE | DELETE request using Axios |


### FetchAPI

| Command | Description |
| ---- | ---- |
| fetchGET | GET request using fetchAPI |
| fetchPOST | POST request using fetchAPI |

### XHR

| Command | Description |
| ---- | ---- |
| xhrGET | GET request using XHR object |
| xhrPOST | POST request using XHR object |
| xhrPUT | PUT request using XHR object |
| xhrDELETE | DELETE request using XHR object |

### Loops

| Command | Description |
| ---- | ---- |
| for | Simple JS for loop |
| .foreach | JS For-each loop |
| forin | JS for-in loop |
| forof | JS for-of loop |


### Functions

| Command | Description |
| ---- | ---- |
| function | Simple JS function |
| arrowfun | JS arrow function |
| asyncarrowfun | Async JS arrow function |


### Timecontrol Functions

| Command | Description |
| ---- | ---- |
| settimeInterval | JS Timeinterval Function |
| settimeout | JS Timeout Function |


### Console Functions

| Command | Description |
| ---- | ---- |
| log | Logs to console |
| table | Displays JS Objects in table format |
| warn | To log warning message to the console |


### JS Events

| Command | Description |
| ---- | ---- |
| .click | Mouse click event |
| .doubleclick | Mouse double click event |
| .contextmenue | Mouse contextmenue event |
| .domloaded | DOM content loaded event |
| .dragStart | It is fired when an item is dragged |
| .dragEnd | It is fired when a drag operation ends |
| .dragLeave | The dragleave event occurs when a draggable element  leaves a valid drop target |
| .dragOver | The event occurs when the dragged element is over the drop target |
| .drop | The drop event occurs when a draggable element is dropped |
| .focus | When the user focuses on an element |
| .keydown | The onkeydown event occurs when the user is pressing a key (on the keyboard) |
| .keypress | To detect only whether the user has pressed a key |
| .keyup | The event occurs when the user releases a key |
| .load | Load event of JS window object |
| .ondrag | It is fired when an item is being dragged |
| .dragEnter | JS drag enter event |
| .mouseOut | Mouse out event |
| .mouseOver | Mouse over event |
| .resize | When the visitor resizes the window of the browser |
| .submit | When the user submits the form |
| .unload | Unload event of JS window object |
| .wheel | The wheel event fires when the user rotates a wheel button on a pointing device (typically a mouse) |

### Express JS

| Command | Description |
| ---- | ---- |
| expapp | To create express server |
| rtInit | Imports and exports router from express |
| rtGET | Express router to handle GET request |
| rtPOST | Express router to handle POST request |
| rtPUT | Express router to handle PUT request |
| rtDELETE | Express router to handle DELETE request |


### CSS


| Command | Description |
| ---- | ---- |
| cssInit | Starter template for CSS |


## Contribution Guidelines

The quicksnippets thanks to thousands of kind volunteers like you. We welcome all contributions to the community and are excited to welcome you aboard.

### Steps to make your contribution

1. Install git

2. Create a fork of quick-snippets repository

3. clone the fork

4. Create a fresh new branch\
    Working on a separate branch for each issue helps you keep your local work copy clean. You should never work on the main. This will soil your copy of freeCodeCamp and you may have to start over with a fresh clone or fork.

5. Avoid using issue numbers in branches. Keep them short, meaningful and unique.

6. Make sure you follow the following steps

| 1 | Create a new file in snippets folder according to language or library (The name of the file should be related to the function of the snippet) save the file with <code>.code-snippets</code> extension |
| ----- | ----- |
| 2 | Write code for your snippet contribution. The snippet object must have following attributes <br> a. Prefix <br> b. Body <br> c. Description|
| 3 | Add the snippet file in the package.json file with appropriate path |
| 4 | Test the extension locally. <br> For <br><code>for Windows</code> <br>Go to C:/Users/.vscode/extension and paste the  quick snippets folder and restart the VS code |
| 5 | Commit the changes <code>git commit -m "Commit message" </code> |
| 6 | Push the changes to your fork and open a pull request |

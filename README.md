# BIC21203 Lab 4b - JSON and jQuery

Name: TAN HUEY LYM
Matric No: AI250211

## Description
Solutions for Lab 4b using JSON, the `fetch()` API and jQuery 4.0.0.

## How to run
1. Open the folder in VS Code.
2. Right-click `books.html` and choose Open with Live Server (do not use file://).
3. Open `jquery-dom.html` in the browser.

## Screenshots

### Q1 - Create and Structure JSON Data
`books.json` has a top-level `books` array with two book objects. Each has `title`, `author`, `publicationYear` (number) and `genres` (array of strings).

![books.json](<screenshot/q1-json.png>)
![JSON validation](<screenshot/q1-jsonlint.png>)

### Q2 - Retrieve and Display JSON Data
`books.html` uses `fetch()` to read `books.json`. It displays the first book title, the second book author and the genres of both books, using `textContent` and `createElement()`. If loading fails, an error message is shown.

![Output](<screenshot/q2-output.png>)
![Error message](<screenshot/q2-error.png>)

### Q3 - Compare Native JavaScript and jQuery
`jquery-dom.html` uses `.text()` to change the text, `.addClass()` to add the `myStyle` class, and `.on("click", ...)` to show an alert.

![After load](<screenshot/q3-before.png>)
![Button alert](<screenshot/q3-alert.png>)

## Native JavaScript vs jQuery
- **Native JavaScript advantage:** it needs no extra library, so pages load faster and have fewer dependencies.
- **Why a project may still use jQuery:** an older project or plugin built on jQuery may keep using it rather than being rewritten.
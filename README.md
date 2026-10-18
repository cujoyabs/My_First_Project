# My_First_Project

A simple to-do list app built with plain HTML, CSS and JavaScript. It has no frameworks, libraries or build step.

## Features

- Add items by typing in the box and pressing **Add** (or Enter)
- Check off items with the checkbox (completed items are crossed out)
- Delete items with the **Delete** button
- Items are saved in your browser, so they are still there after you refresh the page

## How to run it

Open `index.html` in any web browser. That's it, no installation needed.

## What each file does

| File | Purpose |
| --- | --- |
| `index.html` | The **structure** of the page. It holds the title, the form with the text box and Add button, the empty list that items get added to, and a message shown when the list is empty. It also loads `style.css` and `script.js`. |
| `style.css` | The **appearance** of the page. It centers the app in a white card and styles the input, buttons and list rows. It also crosses out and greys completed items (the `.done` class). |
| `script.js` | The **behavior** of the page. It keeps the to-dos in an array, and its `addTodo`, `toggleTodo` and `deleteTodo` functions change that array. After each change it calls `render()` to redraw the list and saves the array to the browser's `localStorage` so it persists between visits. |
| `README.md` | This file, which describes the project. |

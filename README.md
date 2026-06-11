# Todo List App

A fully functional Todo List application built with Vanilla JavaScript using The Elm Architecture (TEA) pattern.

Users can add, edit, delete and filter todo items. Data is saved to localStorage so todos persist after page refresh.

## Stack

- **Frontend:** Vanilla JavaScript, HTML, CSS (TodoMVC styles)
- **Architecture:** The Elm Architecture (TEA)
- **Testing:** Tape + JSDOM
- **Backend:** None
- **DB:** localStorage

## How to run locally

```bash
git clone https://github.com/Zappy8922/todo-list-app.git
cd todo-list-app
npm install
```

Then open `index.html` with Live Server in VS Code.

## Deploy

https://todo-list-nxtqfjppw-cubby-projects1.vercel.app 

## Architecture

The app follows The Elm Architecture (TEA) pattern with three core parts:

- **Model** - the app state (list of todos, current route)
- **Update** - pure function that transforms the model based on actions
- **View** - renders the model to the DOM

## Features

- Add new todo items
- Edit existing items (double-click)
- Delete items
- Mark items as complete
- Filter by All / Active / Completed
- Data persists in localStorage
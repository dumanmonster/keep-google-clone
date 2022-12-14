# Clone Google Keep

> Google keep is a note-taking service. <br>
> Clone google keep application using react and typescript as a web app.

I tried to clone the details of an actual Google Keep application for a test task.
By developing this app, I focused on basic concepts of react and typescript, a functional component, and its ecosystem. And I also tried to optimize its performance and write clean and simple code.

<br>

## Live demo

You can check demo [here](https://keep--clone-b04b3.web.app/).

<br>


## 💫 Features

- Custom note (color, pin, archive, label, todo list).
- CRUD of note and label in real time.
- Filtering of note.
- Draggable todo item.
- Social login (email, google, github).

<br>

## Tech and libraries

- React (create-react-app)
- Typescript
- Redux
- Redux-thunk
- Firebase
- immutability-helper
- react-dnd & react-dnd-html5-backend
- material-ui
- Styled-components
- react-masonry-css
- react-transition-group

<br>

## Getting started

### Prerequisites

- Firebase Account
- Your own firebase API

<br>

### Firebase Setup

- Create a project(web) and a clouse firestore.
- Setup Sign-in method by enabling email/password, google, and github in Authentication tab.

### Install

- Add the following env variables to .env file

```
REACT_APP_API_KEY={apiKey}
REACT_APP_AUTH_DOMAIN={authDomain}
REACT_APP_DATABASE_URL={databaseUrl}
REACT_APP_PROJECT_ID={projectId}
REACT_APP_STORAGE_BUCKET={storageBucketURL}
REACT_APP_MESSAGING_SENDER_ID={messagingSenderId}
REACT_APP_APP_ID={appId}
```

Make sure to add "REACT*APP*" before variables if you use create-react-app.

- Install npm packages

```bash
npm install
```

- Start dev server

```bash
npm start
```

<br>



---

## Improvements

- Save "isDone" property of a todo item in order to save checked value of a checkbox.
- Update label from all notes when edit a global label.
- Truncate Todo Item.

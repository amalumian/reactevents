# ReactEvents

ReactEvents is a multi-page SPA with React Router.

Made on [Maximilian Schwarzmüller's course](https://www.udemy.com/course/react-the-complete-guide-incl-redux/).

## How to run this project

This project actually contains two projects:

- A React.js application (i.e., the frontend SPA)
- A dummy backend API to which the React app can "talk" (to send + fetch data)

You must run "npm install" in both project folders.

Thereafter, you can start the dummy backend API server via "npm start" (inside the "backend-api" folder).
The React app dev server is then also started via "npm start" (though inside the "react-frontend" folder).

You MUST have both servers (backend + frontend) up and running for the projects to work.

The dummy backend API does not use any external database - instead the dummy data is saved to an "events.json" file inside the project folder.

## Screenshot

![screenshot](https://i.imgur.com/ry5hLac.png)

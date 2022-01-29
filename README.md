# Go/ReactJS Web Chat application

This is a simple chat web app that used ReactJS for the frontend and Go for the backend. It uses the [Gorrila Websocket](https://github.com/gorilla/websocket) implementation of the WebSocket protocol to handle communication between multiple instances.

The frontend is built with React. It uses an API to communicate with the backend and listen for messages. Sass is also used for cleaner and minimized css. It is based on [Tutorial Edge](https://github.com/TutorialEdge/realtime-chat-go-react)'s github repo.

The backend uses Go.

### Setup

To get the file running, first clone the repository by typing

    https://github.com/merziy/go-react-chat-app.git

on your commandline. Then:

    cd /frontend
    npm install
    npm start

navigating to the backend to start the Docker container,

    cd /backend
    docker build -t backend .
    docker run -it -p 8080:8080 backend

which should start the backend.

<div align="center">

# Journal App

Journaling tool to save your notes/prompts and manage them separately.

[Client Repo](https://github.com/almeidavc/journal-app-client) •
[Server Repo](https://github.com/almeidavc/journal-app-server)

</div>

## Overview

Implemented a full-stack web application in JavaScript, including a REST API using Node.js for the backend with PostgreSQL as the database. Built with:

- React, React Router
- Tailwind CSS
- Express
- PostgreSQL

## App Demo

![App Demo](https://raw.githubusercontent.com/almeidavc/journal-app-client/master/app-demo.gif)

## Backend Architecture

![Backend Architecture](https://raw.githubusercontent.com/almeidavc/journal-app-server/master/backend-architecture.png)

## API Endpoints

| URI           | Method | Description                                 |
| ------------- | ------ | ------------------------------------------- |
| /prompts      | GET    | Read all prompts                            |
| /prompts/{id} | GET    | Read prompt                                 |
| /prompts      | POST   | Create a new prompt                         |
| /prompts/{id} | PUT    | Update prompt                               |
| /prompts/{id} | DELETE | Delete prompt                               |
| /drafts       | GET    | Read all drafts                             |
| /drafts-md    | GET    | Read all drafts metadata (without the body) |
| /drafts/{id}  | GET    | Read draft                                  |
| /drafts       | POST   | Create a new draft                          |
| /drafts/{id}  | PUT    | Update draft                                |
| /drafts/{id}  | DELETE | Delete draft                                |

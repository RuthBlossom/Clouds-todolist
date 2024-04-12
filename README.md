# To-Do List Web Application

This is a simple to-do list web application built with Node.js, Express.js, MongoDB, and EJS templating engine.

## Features

- **Add Items**: Users can add new to-do list items.
- **Delete Items**: Users can delete existing to-do list items.
- **Custom Lists**: Users can create custom lists with their own titles.
- **Default Items**: Each list (including custom lists) starts with some default items.
- **About Page**: Provides information about the application.

## Prerequisites

Before running the application, ensure you have the following installed:

- Node.js
- MongoDB

## Installation

1. Clone this repository:


2. Navigate to the project directory:

```
cd todo-list
```

3. Install dependencies:

```
npm install
```

4. Start the server:

```
npm start
```

## Usage

- Access the application by navigating to `http://localhost:3000` in your web browser.
- To create a custom list, enter the desired list name in the URL, e.g., `http://localhost:3000/yourcustomlist`.
- Add items to your lists and delete them as needed.

## Configuration

- The MongoDB connection URI is located in `app.js`. Change this URI to connect to your MongoDB database.

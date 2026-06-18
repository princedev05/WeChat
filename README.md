# WeChat

A real-time chatting application built using **Node.js**, **Express.js**, and **Socket.IO**. It enables multiple users to communicate instantly through WebSockets.

## Features

* Real-time messaging using Socket.IO
* Lightweight and easy to set up
* Built with Node.js and Express.js

## Getting Started

### 1. Clone the Repository

```bash
git clone <repository-url>
cd WeChat
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Create the Public Folder

Create a folder named `public` in the project root directory and move `index.html` into it.

Project structure should look like:

```
WeChat/
│
├── public/
│   └── index.html
├── server.js
├── package.json
└── node_modules/
```

### 4. Start the Application

Run the server using Nodemon:

```bash
nodemon server.js
```

The application will start, and you can access it in your browser at:

```
http://localhost:9000
```

## Technologies Used

* Node.js
* Express.js
* Socket.IO

## Author

**Prince**

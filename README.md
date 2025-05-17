<div align="center">
  <h1>Welcome to Memories App 👋</h1>
  <h3>Website for this Project Repository : <a href="https://memoriesmernshreya.netlify.app/">Click Here!</a></h3>
</div>

<p align="center">
<a href="https://github.com/shreya024"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat&logo=github"></a> 
<a href="https://github.com/shreya024"><img src="https://img.shields.io/badge/Open%20Source-%F0%9F%A4%8D-Green"></a> 
<a href="https://github.com/shreya024"><img src="https://img.shields.io/static/v1.svg?label=Contributions&message=Welcome&color=0059b3&style=flat-square"></a>
<a href="https://github.com/shreya024/MemoriesApp/graphs/contributors"><img src="https://img.shields.io/github/contributors-anon/shreya024/MemoriesApp"></a>
<a href="https://github.com/shreya024"><img src="https://img.shields.io/maintenance/yes/2022"></a>
</p> 

<p align="center">
<a href="https://github.com/shreya024/MemoriesApp/stargazers"><img src="https://badgen.net/github/stars/shreya024/MemoriesApp"></a>
<a href="https://github.com/shreya024/MemoriesApp/network/members"><img src="https://badgen.net/github/forks/shreya024/MemoriesApp"></a>
<a href="https://github.com/shreya024/MemoriesApp/issues"><img src="https://badgen.net/github/open-issues/shreya024/MemoriesApp"></a>
<a href="https://github.com/shreya024/MemoriesApp/issues?q=is%3Aissue+is%3Aclosed"><img src="https://badgen.net/github/closed-issues/shreya024/MemoriesApp"></a>
<a href="https://github.com/shreya024/MemoriesApp/pulls"><img src="https://badgen.net/github/prs/shreya024/MemoriesApp"></a>
<a href="https://github.com/shreya024/MemoriesApp/pulls?q=is%3Apr+is%3Aclosed"><img src="https://badgen.net/github/closed-prs/shreya024/MemoriesApp"></a>
</p>

## 📝 About the Project

Memories App is a full-stack MERN (MongoDB, Express, React, Node.js) application that allows users to create, view, update, delete, and like memory posts. The application provides a beautiful and responsive user interface for managing personal memories with images, tags, and descriptions.

## ✨ Features

- 📱 Responsive design that works on desktop and mobile
- 🔐 User authentication and authorization
- 📝 Create, read, update, and delete memory posts
- ❤️ Like memory posts
- 🔍 Search memories by title or tags
- 🏷️ Filter memories by tags
- 📷 Upload images for memories
- 📱 Progressive Web App (PWA) capabilities

## 🛠️ Tech Stack

### Frontend
- React.js
- Redux for state management
- Material-UI for styling
- Axios for API requests
- React Router for navigation

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT for authentication

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm or yarn
- MongoDB Atlas account or local MongoDB installation

### Installation

#### Clone the repository

```bash
git clone https://github.com/shreya024/MemoriesApp.git
cd MemoriesApp
```

#### Backend Setup

1. Navigate to the server directory
```bash
cd server
```

2. Install dependencies
```bash
npm install
```

3. Create a `.env` file similar to the `.env.example`

4. Start the server
```bash
npm run dev
```

The server will run on http://localhost:5000

#### Frontend Setup

1. Navigate to the client directory
```bash
cd ../client/memories
```

2. Install dependencies
```bash
npm install
```

3. Start the client
```bash
npm start
```

The client will run on http://localhost:3000

## 📚 API Documentation

The API provides the following endpoints:

- **GET /posts** - Get all posts (with pagination)
- **GET /posts/:id** - Get a specific post
- **POST /posts** - Create a new post
- **PATCH /posts/:id** - Update a post
- **DELETE /posts/:id** - Delete a post
- **PATCH /posts/:id/likePost** - Like a post

For detailed API documentation, check the [PostMan Collection](https://www.getpostman.com/collections/c4646abd46f3fff405f8)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## ⚙️ Things to Note

* Make sure you do not copy code from external sources because that work will not be considered. Plagiarism is strictly not allowed.
* You can only work on issues that have been assigned to you.
* If you want to contribute and make a change, it's preferable that you create a new issue before making a PR and link your PR to that issue.
* If you have modified/added code, make sure the code compiles before submitting.
* Add screenshots and short videos to help us know what this change in the PR is all about.

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📧 Contact

If you have any questions, feel free to reach out to the project maintainers.

## 🙏 Acknowledgements

- [React](https://reactjs.org/)
- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Material-UI](https://material-ui.com/)
- [Redux](https://redux.js.org/)
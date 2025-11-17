# book-review-api
Book Review Application using Node.js + Express (IBM project)
# 📚 Book Review Application — Node.js + Express  
IBM Full Stack Software Developer – Final Project

This project implements a complete **Book Review API** using Node.js and Express.  
It supports public book browsing, user registration, login, and adding/modifying/deleting reviews by authenticated users.

It also includes **four Node.js methods using Axios** (Callback, Promises, Async/Await) as required in Tasks 10–13.

---

## 🚀 Features

### 🔓 **Public Endpoints (General Users)**
| Task | Description | Endpoint |
|------|-------------|----------|
| Task 1 | Get all books | `GET /books` |
| Task 2 | Get book by ISBN | `GET /books/isbn/:isbn` |
| Task 3 | Get books by author | `GET /books/author/:author` |
| Task 4 | Get books by title | `GET /books/title/:title` |
| Task 5 | Get book reviews | `GET /books/review/:isbn` |
| Task 6 | Register a new user | `POST /register` |
| Task 7 | Login as a registered user | `POST /login` |

---

### 🔐 **Authenticated Endpoints (Registered Users Only)**
| Task | Description | Endpoint |
|------|-------------|----------|
| Task 8 | Add/Modify book review | `PUT /auth/review/:isbn` |
| Task 9 | Delete user’s review | `DELETE /auth/review/:isbn` |

JWT is used for authentication.

---

## 🧑‍💻 **Node.js Methods (Tasks 10–13)**

| Task | Method | Description | File |
|------|--------|-------------|------|
| Task 10 | Callback | Get all books | `/methods/callback.js` |
| Task 11 | Promises | Search by ISBN | `/methods/promise.js` |
| Task 12 | Promises | Search by Author | `/methods/author.js` |
| Task 13 | Async/Await | Search by Title | `/methods/async.js` |

Run them with:

```bash
npm run methods:callback
npm run methods:promise
npm run methods:author
npm run methods:asynce

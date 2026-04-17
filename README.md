# 📝 Blog REST API with Express

A simple **Blog REST API built with Node.js and Express** that allows users to create, read, update, and delete blog posts.

This project also includes a small **frontend client using EJS and Axios** that interacts with the API.

---

## 🚀 Features

* View all blog posts
* View a single blog post
* Create a new blog post
* Edit an existing post
* Delete a blog post
* REST API built with Express
* Frontend using **EJS templates**

---

## 🖼 Screenshots

*(Add your screenshots here)*

Example:

![Homepage](screenshots/home.png)

![Create Post](screenshots/create.png)

![Edit Post](screenshots/edit.png)

---

## 🛠 Tech Stack

* Node.js
* Express.js
* Axios
* EJS
* Body Parser

---

## 🔌 API Endpoints

GET all posts

```
GET /posts
```

GET a specific post

```
GET /posts/:id
```

Create a new post

```
POST /posts
```

Update a post

```
PATCH /posts/:id
```

Delete a post

```
DELETE /posts/:id
```

---

## ⚙️ Running the Project

Install dependencies

```
npm install
```

Start API server

```
node index.js
```

Start frontend server

```
node server.js
```

API runs on

```
http://localhost:4000
```

Frontend runs on

```
http://localhost:3000
```

---

## 📌 Note

This project uses an **in-memory data store**, so all posts reset when the server restarts.

---

## 👩‍💻 Author

Built using **Node.js and Express**.

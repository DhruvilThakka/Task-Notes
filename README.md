# 📝 Notes App (MERN Stack)

A simple full-stack CRUD Notes App built with:

- **MongoDB** (Database)
- **Express.js** (Backend)
- **React.js** (Frontend)
- **Node.js** (Runtime)

---

## 📁 Project Structure


---

## 🚀 Features

- Create, Read, Update, Delete notes
- Notes are sorted by latest created
- Uses MongoDB Atlas for cloud database
- Modern React (Hooks, Axios)
- Clean and minimal UI

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd notes-app


cd server
npm install


MONGO_URI=mongodb+srv://USERNAME:PASSWORD@cluster0.mongodb.net/notesdb
PORT=5000

npm start

cd ../client
npm install

"proxy": "http://localhost:5000"

npm start

| Method | Endpoint         | Description     |
| ------ | ---------------- | --------------- |
| GET    | `/api/notes`     | Get all notes   |
| POST   | `/api/notes`     | Create new note |
| PUT    | `/api/notes/:id` | Update a note   |
| DELETE | `/api/notes/:id` | Delete a note   |

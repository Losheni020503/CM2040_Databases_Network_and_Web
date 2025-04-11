# 📝 Losh Blog – Full-Stack Blogging Platform

Losh Blog is a fully functional blogging tool built using **Node.js**, **Express.js**, **SQLite**, **EJS**, and **Bootstrap/Tailwind CSS**. It supports user registration, authentication, authoring tools, comment systems, and a like feature. Users can read, comment, and like posts while authors can publish, update drafts, and manage blog settings.

---

## 🗓️ Project Duration

**December 2023 – January 2024**

---

## 🚀 Features

### 👨‍💻 Author Features
- Create and edit blog articles (published or draft)
- Modify blog title and subtitle
- View and delete articles
- Save draft before publishing
- AJAX-based deletion and publishing

### 👥 Reader Features
- Browse published articles
- Comment on articles
- Like/unlike articles (AJAX)
- Real-time like and comment updates

### 🔐 Authentication
- Login and registration for both readers and authors
- Session-based user roles (author vs reader)

### 💡 UI and UX
- Built using **EJS** templating and **Bootstrap CSS**
- Responsive layout and dynamic navigation
- Clean author/reader dashboards

---

## 🧱 Tech Stack

| Layer        | Technologies Used              |
|--------------|--------------------------------|
| Backend      | Node.js, Express.js            |
| Frontend     | EJS, Bootstrap, jQuery         |
| Database     | SQLite3                        |
| Styling      | Tailwind CSS + Bootstrap       |
| Auth         | Express-Session                |

---


---

## 📸 Screenshots

> *(Add screenshots or GIFs here if available, such as the dashboard, reader view, or editor page)*

---

## 💻 How to Run

### 📦 Requirements

- Node.js (v16+ recommended)
- SQLite3

### 🧪 Setup

```bash
# Clone the repo
git clone https://github.com/yourusername/losh-blog.git
cd losh-blog

# Install dependencies
npm install

# Run the app
node app.js
```

## Key Routes
Role	Path	Description
Author	/author	Author dashboard
Reader	/reader	Reader dashboard
Articles	/author/article	Create or update article
Login	/login	Login page
Register	/register	New user registration
API	/article/:id/like	AJAX like/unlike request
Guest	/guest/author	Read-only guest view of author page

## 🎯 Learning Highlights
CRUD operations using SQLite and SQL queries

Separation of concerns with modular routing (author.js, reader.js)

Conditional rendering and partials with EJS

Using AJAX for like and comment interactions without page reloads

Middleware usage for role-based access control

## ⚠️ Known Issues & Improvements

✏️ Error messages could be improved with flash alerts

🔒 Author role is hardcoded – could be expanded to use a full user role model

💬 Comment system could support reply threading in the future

## 👤 Author
Losheni Meenakshi Sundaram
Student at Singapore Institute of Management
📫 Email: losheni.ms@gmail.com

## 🗃️ License
This project is licensed for academic and personal learning use only.

## 🙌 Acknowledgements
Inspired by modern content platforms like Medium and WordPress

Dataset-free: All content user-generated




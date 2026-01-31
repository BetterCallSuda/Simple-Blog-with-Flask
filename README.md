# Simple-Blog-with-Flask
A simple Flask web application that fetches blog post data from an external API and displays posts dynamically using Jinja templates and URL routing.


# Flask Blog Viewer 📝

A lightweight Flask web application that fetches blog post data from an external API and displays it dynamically using server-side rendering.

This project demonstrates Flask fundamentals such as routing, templates, API consumption, and object-oriented design.

---

## 🚀 Features

- Fetches blog posts from a public JSON API
- Displays all blog posts on the home page
- View individual blog posts using dynamic URL routing
- Clean separation of data, logic, and templates
- Uses Flask + Jinja2 for server-side rendering

---

## 🛠 Tech Stack

- **Python**
- **Flask**
- **Jinja2**
- **Requests**
- **HTML / CSS**

---

## 📂 Project Structure

├── app.py
├── post.py
├── templates/
│ ├── index.html
│ └── post.html
├── static/
│ └── styles.css
└── README.md


---

## 🔄 How It Works

1. Blog post data is fetched from an external API.
2. Each post is converted into a `Post` object.
3. The home route (`/`) displays all blog posts.
4. Clicking a post opens a detailed view using a dynamic route (`/post/<id>`).
5. Flask renders HTML templates using Jinja.

---

## ▶️ Run Locally

1. Clone the repository:
```bash
git clone https://github.com/your-username/flask-blog-viewer.git
Install dependencies:

pip install flask requests
Run the app:

python app.py
Open in browser:

http://127.0.0.1:5000

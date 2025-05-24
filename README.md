<h1 align="center">☁️ Cloud Migration of a Flask App using Lift & Shift (AWS) ☁️</h1>

<p align="center">
  <strong>A lightweight e-commerce web app powered by Flask, containerized with Docker, and migrated to AWS using the Lift & Shift strategy.</strong>
</p>

---

<h2 align="center">🛠️ Architecture</h2>

<p align="center">
  <img src="https://github.com/user-attachments/assets/dcf3b2ab-c152-4e39-a802-b62c67ec3297" alt="Lift and Shift Architecture" width="700"/>
</p>

---

## 📦 Overview

Lightweight e-commerce web application built using Flask. It features:

- ✅ User authentication
- 🛒 Product listings
- 🧺 Cart functionality
- 📜 Order history

The application was containerized using Docker and deployed on AWS via:

- EC2 (for hosting the Flask app)
- RDS (for dynamic user and order data)
- S3 (for storing static files like images)

⚠️ The app is not currently live due to AWS cost constraints. This repository serves as a documentation and showcase of the deployment process.

---

## ⚙️ Tech Stack

| Layer       | Technology               |
|------------|---------------------------|
| Backend     | Python (Flask)            |
| Database    | AWS RDS (MySQL)           |
| Frontend    | HTML, CSS, Jinja2         |
| Container   | Docker                    |
| Deployment  | AWS EC2 + S3 + RDS        |
| ORM         | SQLAlchemy                |

---

## 🚀 How to Run Locally

Pull the image:

```bash
docker pull souravangre/flask-fitstore
docker run -p 4000:4000 souravangre/flask-fitstore
```
Then, open http://localhost:4000 in your browser.

<h3 align="center">🏗️ Deployment Architecture</h3> <p align="center"> 🖥️ Flask app runs inside a Docker container on an AWS EC2 instance<br> 💾 MySQL database is hosted using Amazon RDS<br> 📁 Static files (images, CSS) are stored in Amazon S3 </p>

<p align="center"> 👨‍💻 Author</p>
<p align="center"> <strong>Sourav</strong><br/> 🌐 Lift & Shift Cloud Migration Practitioner </p> 


Cloud Migration of a Flask App by Lift & Shift strategy (AWS)

Architechture :
![Lift   Shift](https://github.com/user-attachments/assets/dcf3b2ab-c152-4e39-a802-b62c67ec3297)


Lightweight e-commerce web application built using Flask. It features user authentication, product listings, cart functionality, and order history. The application was containerized with Docker and successfully deployed on AWS using:

 -EC2 (for hosting the Flask app in a Docker container)
 -RDS (for storing dynamic user and order data)
 -S3 (for storing static files like images)

🚫 The app is no longer live due to AWS cost constraints. This repository includes all code and screenshots for demonstration and documentation purposes.

⚙️ Tech Stack
Layer	                Technology
Backend                 Python (Flask)
Database            	AWS RDS (MySQL)
Frontend	            HTML, CSS, Jinja2
Container	            Docker
Deployment	            AWS EC2 + S3 + RDS
ORM                	    SQLAlchemy

🚀 How to Run Locally

docker pull souravangre/flask-fitstore

docker run -p 4000:4000 souravangre/flask-fitstore


🏗️ Deployment Architecture

🖥️ Flask app runs inside a Docker container on an AWS EC2 instance
💾 MySQL database is hosted using Amazon RDS
📁 Static files (images, CSS) are stored in Amazon S3

🧑‍💻 Author:
Sourav 

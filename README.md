🚀 Dockerized Flask App

A simple Python Flask web application containerized using Docker — perfect for DevOps beginners.

📌 Features

Minimal Flask app returning a demo message

Lightweight Docker image (python:3.9-slim)

Easy to build and run

🛠️ Files
app.py
requirements.txt
Dockerfile
README.md

▶️ Run Without Docker
pip install -r requirements.txt
python3 app.py


Open → http://localhost:5000

🐳 Run With Docker
Build Image
docker build -t flask-app .

Run Container
docker run --rm -p 5000:5000 flask-app


Access → http://localhost:5000

Output → Hello from Dockerized Flask!

🧹 Cleanup
docker rmi flask-app

🧑‍💻 What You Learn

Docker image creation

Container execution & port mapping

Flask app deployment workflow

If you like this project ⭐ the repo!
Happy Containerizing! 🐳🔥

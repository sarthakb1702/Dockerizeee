# 🚀 Flask Docker App

This project demonstrates how to containerize a simple Flask web application using Docker.  
It lets you build and run the app inside a Docker container and access it via your browser.

---

## 🐳 Build the Docker image
Run this in your terminal:
```bash
docker build -t flask-docker-app .
```
🚀 Run the container
Start the Flask app container:

```bash
docker run -d -p 5000:5000 flask-docker-app
```
Then open http://localhost:5000 in your browser.

🔎 Verify running container
Check your container:
```bash
docker ps
```
📌 Notes
This app uses Flask as the web framework.

The container exposes port 5000 for access.

# 🐳 Hello World Docker Project

This is a simple Dockerized Python application that prints **"Hello World"** to the console.  
It demonstrates how to build and run a lightweight container using Docker.

---

## 📁 Project Structure
hello-world-docker-project/
│
├── app.py # Simple Python script
└── Dockerfile # Docker configuration


---

## ⚙️ How to Build and Run

### 🧱 Step 1: Build the Docker image
```bash
docker build -t hello-world-docker .

🚀 Step 2: Run the container
docker run hello-world-docker

Expected Output:
Hello World

Hanumat Kripa ❤️
# Node Docker App 🚀

A simple **Node.js Express application** containerized using **Docker**.  
This project demonstrates how to build, run, and deploy a Node.js app using Docker and Docker Hub.

---

## 📌 Features
- Node.js + Express server
- Dockerized application
- Exposed on port **8000**
- Ready for cloud deployment (AWS / Docker Hub)

---

## 🗂 Project Structure
node-docker-app/
├── main.js
├── Dockerfile
├── package.json
├── package-lock.json
└── .gitignore
---

## ▶️ Run Locally (Without Docker)

```bash
npm install
node main.js

http://localhost:8000

docker build -t node-app .
docker run -p 8000:8000 node-app

📦 Docker Hub Image
Pull and run directly from Docker Hub:
docker pull deepaktiwariii/node-app:latest
docker run -p 8000:8000 deepaktiwariii/node-app:latest
Returns "Hello World message"

🛠 Tech Stack
	•	Node.js
	•	Express.js
	•	Docker

	•	Docker Hub: https://hub.docker.com/u/deepaktiwariii

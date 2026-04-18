# Docker Project 1 🚀

This is a simple project to learn how to run an application inside a Docker container.

## 📌 What I am building
- A basic web app running inside a Docker container
- Using Nginx as the web server

## 🛠️ Technologies Used
- Docker
- Nginx
- HTML/CSS (basic frontend)

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/tanmayjain227/docker-project1.git
cd docker-project1

2.Build Docker image:
```bash
docker build -t my-docker-app .

3.Run container:
```bash
docker run -d -p 8080:80 my-docker-app
4.Open in browser:
```bash
http://localhost:8080

📚 What I Learned
How Docker containers work
How to create a Dockerfile
How to run and expose ports

🚧 Future Improvements
Add Kubernetes deployment
Add CI/CD pipeline

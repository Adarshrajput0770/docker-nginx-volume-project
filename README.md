# 🚀 Docker Nginx Volume Project

This is a simple DevOps project where I deployed a static website using Docker and Nginx with Volume Mount for live updates.

## 📌 Project Description
In this project, I used the official Nginx Docker image and mounted a local folder as a volume to enable real-time website updates without rebuilding the Docker image.

## 🛠️ Technologies Used
- Docker
- Nginx
- HTML
- Git & GitHub

## How to Run the Project

### Step 1: Clone the repository
git clone git clone https://github.com/Adarshrajput0770/docker-nginx-volume-project.git

### Step 2: Go to project folder
cd nginx-volume-project

### Step 3: Run Nginx container with volume
docker run -d -p 8081:80 -v $(pwd):/usr/share/nginx/html nginx

### Step 4: Open in browser
http://localhost:8081

## Key Features
- Live website update without rebuilding Docker image
- Volume Mount concept implementation
- Beginner-friendly DevOps project
- Fast development workflow

## Project Structure
nginx-volume-project/
│── index.html
│── README.md

## Author
Adarsh – DevOps & Cloud Learner

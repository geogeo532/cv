# 📄 DevOps Resume – Daniel-George Corbeanu

This project is a **resume website** built using plain HTML & CSS, containerized using **Docker**, automated with **GitHub Actions**, and deployed to the cloud via **Render**.

🌐 **Live Demo:** [https://devops-cv.onrender.com](https://devops-cv.onrender.com)  
🐳 **DockerHub:** [geogeo532/devops-cv](https://hub.docker.com/r/geogeo532/devops-cv)  
📦 **GitHub Repo:** [github.com/geogeo532/cv](https://github.com/geogeo532/cv)

---

## 🛠️ Tech Stack

- HTML / CSS (custom layout for a professional resume)
- [NGINX](https://nginx.org/) for static file serving
- [Docker](https://www.docker.com/) for containerization
- [GitHub Actions](https://github.com/features/actions) for CI/CD
- [DockerHub](https://hub.docker.com/) for image registry
- [Render](https://render.com/) for live deployment

---

## 🚀 How it works

1. `index.html` is copied into an NGINX Docker container
2. GitHub Actions builds the Docker image and pushes it to DockerHub
3. Render pulls the image and deploys it to a live URL
4. Any push to the `main` branch triggers automatic rebuild & redeploy

---

## 📂 Project structure


# 🌟 Portfolio Website

Welcome to my personal portfolio website! This project showcases my work, skills, and projects. It is built using **Bootstrap** for a responsive and visually appealing design and is containerized using **Docker** for easy deployment.

---

## ✨ Features

- **📱 Responsive Design:** Fully optimized for all screen sizes.
- **🎨 Modern UI:** Built with the latest version of Bootstrap.
- **🐳 Dockerized:** Easily deployable as a Docker container.
- **💼 Projects Showcase:** Highlights my key projects and skills.

---

## ⚙️ Prerequisites

Before running the project, ensure you have the following installed:

- [🐋 Docker](https://www.docker.com/get-started)  
- A web browser to view the site.

---

## 🚀 Installation and Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/portfolio-site.git
cd portfolio-site
```

### 2️⃣ Build the Docker Image
```bash
docker build -t portfolio-site .
```

### 3️⃣ Run the Docker Container
```bash
docker run -p 8080:80 portfolio-site
```

### 4️⃣ Access the Website
Open your browser and visit:  
`http://localhost:8080`

---

## 📂 Folder Structure

```plaintext
portfolio-site/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
│   └── ...
├── Dockerfile
└── README.md
```

---

## 🐳 Dockerfile

Below is the Dockerfile used to containerize the application:

```dockerfile
# Use the official Nginx image as a base
FROM nginx:alpine

# Copy website files to the Nginx web root
COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 80
```

---

## 🛠️ Technologies Used

- **📄 HTML5** and **🎨 CSS3**
- **📦 Bootstrap**
- **📜 JavaScript**
- **🐳 Docker**

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

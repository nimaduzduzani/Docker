# 🐳 WordPress with Docker Compose

This project sets up a **WordPress** environment using **Docker Compose**.  
It provides a quick and easy way to run WordPress locally with minimal configuration.

---

## 📦 Project Overview

This stack includes:
- **WordPress** (latest version)
- **MySQL** as the database

---

## 🚀 Getting Started

Make sure you have Docker and Docker Compose installed on your system.

### 1️⃣ Build the containers
```bash
docker compose build
```
---

### 2️⃣ Start the containers in detached mode
```bash
docker compose up -d
```

---

### 🌐 Access WordPress

Once the containers are running, open your browser and go to:

```bash
http://localhost:8080
```
From there, you can complete the WordPress installation and start developing.

---

### 🧹 Stopping and Cleaning Up

To stop and remove all containers, networks, and volumes:

```bash
docker compose down
```

---

## 🛠️ Notes

- Default WordPress port: 8080
- Database credentials and configuration are defined inside the docker-compose.yml file.
- You can modify ports and volumes as needed for your setup.

---

## 🧑‍💻 Author

Created by **Nima Fakhr**

A practical example of deploying **WordPress** with **Docker Compose**, showcasing containerized web and database services.


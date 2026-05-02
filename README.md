# CodeAlpha DevOps Internship - Task 4: Web Server using Docker

## 🚀 Project Overview
This project demonstrates the deployment and management of a static web server using **Nginx** inside a **Docker Container**. This task is part of my DevOps Internship at **CodeAlpha**, focusing on the **Container Lifecycle** and **Cloud Deployment**.

## 🛠 Tech Stack
*   **Web Server:** Nginx (Alpine-based for efficiency)
*   **Containerization:** Docker
*   **CI/CD & Hosting:** Render
*   **Version Control:** GitHub

## 📁 Project Structure
*   `Dockerfile`: Contains instructions to build the Nginx image and copy custom HTML.
*   `index.html`: A custom landing page for the EcoBridge project.
*   `README.md`: Documentation of the task.

## ⚙️ How to Run Locally
1. **Build the image:**
   ```bash
   docker build -t nginx-task4 .

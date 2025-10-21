# 🧮 Calculator App (JavaScript)

A simple calculator web app built with **JavaScript** that supports basic arithmetic operations — **addition**, **subtraction**, **multiplication**, and **division**.  
This project focuses on demonstrating **CI/CD pipeline automation**, **Dockerization**, and **unit testing** integration.

---

## 🚀 Features

- Add, Subtract, Multiply, and Divide operations
- Fully containerized using **Docker**
- Automated testing using **Jest**
- Continuous Integration and Deployment (CI/CD) via **GitHub Actions**
- Docker image automatically pushed to **Docker Hub**

---

## 🧩 Tech Stack

- **Language:** JavaScript (Node.js)
- **Testing Framework:** Jest
- **Containerization:** Docker
- **CI/CD:** GitHub Actions
- **Image Registry:** Docker Hub

---

## 🧮 Example Usage

```bash
node src/index.js
```

## 🧪 Running Tests

Run all unit tests using Jest:

````
npm install
npm test
````
## 🐳 Docker Setup
Build Docker Image
````
docker build -t simple-calculator .
````

## ⚙️ CI/CD Pipeline
### Pipeline Overview

**The pipeline includes:**
- Install dependencies
- Run unit tests
- Build Docker image
- Push Docker image to Docker Hub

## 🔒 Environment Variables

If needed, create a `.env` file to store configuration values (optional for this project).

## 🧠 Future Enhancements

- Add a simple web frontend (HTML/CSS)
- Add scientific functions (square root, exponent, etc.)
- Deploy to AWS / Render / Vercel
- Add integration tests

## 🏁 Summary

- This project demonstrates:
- Writing clean modular JS code
- Implementing Jest unit tests
- Building and pushing Docker images
- Setting up automated CI/CD pipelines with GitHub Actions
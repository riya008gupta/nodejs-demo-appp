# nodejs-demo-app

This is a simple Node.js web application built to demonstrate basic **CI/CD pipeline** integration and Docker containerization.

## 🚀 Features

- Basic Node.js HTTP server
- Dockerized setup
- Runs on port `3000`
- Message: `"Hello Riya! CI/CD Pipeline Working ✅"`

## 🛠️ Technologies Used

- Node.js
- Docker

## 📦 Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/riya008gupta/nodejs-demo-appp.git
cd nodejs-demo-appp
2. Build Docker Image
bash
Copy
Edit
docker build -t riya-node-app .
3. Run the Docker Container
bash
Copy
Edit
docker run -p 3000:3000 riya-node-app
4. Open in Browser
Visit: http://localhost:3000

You’ll see:

nginx
Copy
Edit
Hello Riya! CI/CD Pipeline Working ✅
📁 Project Structure
pgsql
Copy
Edit
nodejs-demo-appp/
├── Dockerfile
├── index.js
└── package.json

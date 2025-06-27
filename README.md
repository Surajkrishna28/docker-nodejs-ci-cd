A simple Node.js app built with Docker and integrated with GitHub Actions.


- Node.js web server
- Docker containerization
- GitHub Actions CI pipeline (Docker build)

# 🧪 Run Locally
```bash
docker build -t my-node-app .
docker run -p 3000:3000 my-node-app

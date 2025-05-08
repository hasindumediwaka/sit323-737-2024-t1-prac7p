# sit323-737-2024-t1-prac7p
This project demonstrates deploying a Node.js CRUD application with a MongoDB backend using Docker and Kubernetes. It covers containerization, service configuration, secret management, and persistent storage setup.
## ⚙️ Setup Instructions
.
├── Dockerfile # Dockerfile for Node.js app
├── mongo-deployment.yaml # MongoDB Deployment + Service
├── mongo-secret.yaml # MongoDB credentials as Kubernetes Secret
├── mongo-pv.yaml # Persistent Volume for MongoDB
├── mongo-pvc.yaml # Persistent Volume Claim for MongoDB
├── app-deployment.yaml # Node.js App Deployment
├── node-service.yaml # Node.js Service (NodePort)
├── src/
│ └── index.js # Node.js CRUD app code
└── README.md # Project documentation


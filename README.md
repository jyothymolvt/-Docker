# Docker
🐳 Docker is a platform that uses containerization technology to package applications and their dependencies into lightweight, portable containers

🔧 Key Concepts:

📄 Dockerfile
Dockerfile is a script that contains instructions to build a Docker image.

📄 Docker Compose (compose.yaml)
A compose.yaml file is used to define and run multi-container Docker applications. It conatines a set of instructions including images,volumes,networks that can be used for creating a docker-based applications.

📦 Docker images
Docker images are executable packages that are build with software packages,application code and its dependencies used for creating containers that can run consistently across any compatible environment.

💾 Docker Volumes

Docker Volumes are used to store data persistently outside of containers.
They allow data to survive container restarts, rebuilds, and removals, making them ideal for databases and user-generated content.

🌐 Docker Networks
Docker Networks allow containers to communicate with each other securely and efficiently.By default, Docker Compose creates a bridge network.

This project demonstrates containerisation of a simple Node.js web app using Docker and Docker Compose.

## Steps

1. Clone repo
2. Build Docker image
3. Run Docker Compose
4. Test app at `http://localhost:3000`
5. Health checks added in `docker-compose.yml`
6. Docker image pushed to DockerHub

## Commands

```bash
docker build -t my-node-app .
docker-compose up
docker push akashgajjala10/my-node-app

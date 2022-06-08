# Docker-Node  🐳
 
Project created to learn about Docker, docker compose, dockerfile and node

### Build Dockerfile

docker bulid -t 'name/name''path'

#### This program

docker build -t dockernode/dockernode .

### Run Dockerfile

docker run -p port/port -d 'nameContainer'

### This

docker run -p 3000:3000 -d dockernode/dockernode

### Run docker-compose.yml

docker compose up 

This command is general for all compose type;

Be Happy ! 😊👌

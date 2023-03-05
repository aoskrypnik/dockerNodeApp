# dockerNodeApp
Devops Lab 3

1. docker build . -t aoskrypnik/node-web-app:v4 – build image
2. docker run -p 80:80 aoskrypnik/node-web-app:v4 – run on port 80
3. docker run -it --cpus=".5" --memory=512m aoskrypnik/node-web-app:v4 – guarantees the container at most 50% of the CPU every second and up to 512m memory.
4. docker push aoskrypnik/node-web-app:v4 – push to Dockerhub

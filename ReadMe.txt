To build image
docker build -t (image_name):(Tag) .

To check docker images
docker images

To run the Docker nginx image
docker run -d -p 8080:80 --name nginx-server (image_name):(Tag)

To check all container available
docker container ls

To check running container 
docker ps

To check stopped container
docker ps -a

To stop container
docker stop (container_name)

To delete container
docker rm -f (container_name)

To delete all stopped container at once 
docker container prune

To delete image 
docker image rm (image_name)



===================================================================================================

#This Application runs in linux containers.

#Prerequestics
    *Docker Desktop community latest stable/edge channel edition.

#First switch your docker desktop client to Linux containers.
#navigate to project root directory 

#verify the container using 
PS> docker version

#Execute the command docker-compose up to run the container
#It'll build the image as per the Dockerfile, create and -  
 run the container as per the docker-compose.yml file instructions.

PS>docker-compose up

#Once the container started navigate to http:\\localhost:8080\jdb-ser-demo

#To stop the container and remove it
PS> docker-compose down

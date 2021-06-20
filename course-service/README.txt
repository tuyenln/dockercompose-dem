Build docker image:
    #build all in curent directory
    docker build -t my-node-app:v0.0.1 .

Run docker image builded:
    #Bind image my-node-app:v0.0.1 with docker port 8080 to real pc with port 5001
    docker run -p 5001:8080 my-node-app:v0.0.1

Stop container via Container ID :
    docker container stop 88d52d1bc45b
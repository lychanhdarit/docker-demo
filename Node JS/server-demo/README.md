 
docker build . -t ricly/app

docker images

docker run -p 5000:8080 -d ricly/app


 # Get container ID
$ docker ps

# Print app output
$ docker logs <container id>

docker stop my_container
# Example
Running on http://localhost:8080
=> Running on http://localhost:49160

 
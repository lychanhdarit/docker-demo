 
docker build . -t ricly/app

docker images

docker run -p 4000:80 -d ricly/app


 # Get container ID
$ docker ps

# Print app output
$ docker logs <container id>

docker stop my_container
# Example
Running on http://localhost:80
=> Running on http://localhost:4000

 
mvn package
mvn docker:build
docker run -d -p 8080:8080 springboot-docker-demo
http://{docker-machine-ip}:8080/
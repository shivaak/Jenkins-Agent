Build the Docker image for JDK 17 with maven latest version:
docker build --platform linux/amd64 -t your-dockerhub-username/jenkins-agent:alpine-jdk17-maven -f Dockerfile-jdk17-maven .

Push the images to Docker Hub:
docker push your-dockerhub-username/jenkins-agent:alpine-jdk17-maven

==============================================================================================================

Build the Docker image for JDK 17 with Maven 3.9.7:
docker build --platform linux/amd64 -t your-dockerhub-username/jenkins-agent:alpine-jdk17-maven-3.9.7 -f Dockerfile-jdk17-maven-3.9.7 .

Push the images to Docker Hub:
docker push your-dockerhub-username/jenkins-agent:alpine-jdk17-maven-3.9.7

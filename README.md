Welcome to CIT Technologies!!! (WAR-style)
===============

This is the simplest possible Java webapp for testing servlet container deployments.  It should work on any container and requires no other dependencies or configuration.

docker-tomcat-satylearning
A basic tutorial on running a web app on Tomcat using Docker - SATYLearning - Subscribe my youtube channel

Steps
Install Docker.
Clone this repository - $ git clone https://github.com/chinni4321/helloworld.git
cd helloworld
# from your root directory
$ docker build -t shelloworld .
$ docker run -p 8082:8080 helloworld
$ http://localhost/hello-world-war-1.0.0:8082

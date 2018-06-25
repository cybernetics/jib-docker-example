# Sample 01

This demonstrates the basic implementation of Docker using Dockerfiles and the command line.

To use:

* `cd node-example`
* `docker build -t user1/node-example .`
* `docker run -p 3003:8080 -d user1/node-example`
* Go to http://localhost:3003

* `cd java-example`
* `docker build -t user1/java-example .`
* `docker run -p 3004:8080 -d user1/java-example`
* Go to http://localhost:3004
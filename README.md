# Test Micrometer Spring

### Steps to run

* Run the docker-dev services (./restart.sh) in licensing-service-levitate to start the zipkin
* Start the application and hit localhost:8080/
* Go to localhost:9411 to check the traces. We are also seeing the traces in the logs.
# spring-microservice-demo

Sample Microservice Application with:

Bookkeeping or Catalog Microservice   
Config Server  
Gateway Microservice (TODO) 
Authentication Server (TODO) 

To run, ensure kubernetes and docker are installed and running.    

On cli, from project root directory, do `tilt up` to run the microservices. 

Also on cli, if you have httpie installed (`brew install httpie`), do the following  
to make post and get request to catalog endpoint:  

`http POST http://localhost:9001/books author="kehinde" publisher="adetiloye"`   
`isbn="1232323232" price=9.90 title="Hi"`. 

`http GET http://localhost:9001/books`.

To undeploy microservices do `tilt down`.

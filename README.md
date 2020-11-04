# cloud-developer-project3

In this project I converted the application "Udagram" from being a monolithic application to a microservices based application through:

1- Containerizing each microservice into a seperate docker container (Feed, User and frontend)
2- Using a reverserpoxy container which resolves the issue of running 2 microservices on the same port and routes traffic according to the request recieved 
3- Running the containers in a kubernetes cluster 


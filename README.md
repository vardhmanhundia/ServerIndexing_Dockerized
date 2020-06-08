# ServerIndex_Dockerized
ServerIndexing is a project created over Stack springBoot and Spring data MongoDB. The projects provides with multiple Rest API created by 
Spring Boot Web Pack. The project provides all the basic CRUD operations to mongoDB database with user accessible REST APIs. It also provides
additional features like auto increment and muliple addition, deletion, updation over the database with one request.It also provides an
Customized Exception Response for some operations which could be modified as per the need. We add Swagg UI which is an excellent tool
for documenting of APIs call and provides a very clear and precise documentation for the project. The MongoDB database as well as SpringBoot
server is been contanarized over the docker file for easy and fast deployment and sharing.

### Primary Goals:
1. Contanarize the REST APIs and MongoDB database over docker conatiner for easy and fast deployment.
## Installation
- The [docker installation](https://docs.docker.com/desktop/) includes detailed installation instructions as well as a comprehensive getting started guide for Docker.

## Getting Started
These instructions will get your project running and deployed over Docker Hub.
1. Git clone the reposity with command or fork it to you repository and git clone to that repository:
```
  git clone https://github.com/vardhmanhundia/ServerIndex_Dockerized.git
```
2. Install and run the Docker Hub on you system. You will find a dolphin symbol runnning and complete the login by creating and signing in
to the docker account if account dosen't exists.
3. Open cmd prompt and go to the root directory of the installed file.
4. Now, run the MakeFile for functioning all the operations.
```
  make run 
```
5. As soon as you run the command following things would happen:
  - Would create a new build file using Maven Package ``` ./mvnw clean package -B ```
  - Now it would run the docker-compose.yml file which would create image for mongo with latest pack.
  - It would also build and image file from the latest build jar and push it over the docker container.
6. You can check the rest Apis corresponding to the server with the new Swagg UI documentation which provides a clear idea about all the
APIs in the project.

![ServerRunning](https://github.com/vardhmanhundia/ServerIndexing_Dockerized/blob/master/images/dockerWorking.gif)


## Versions
Please CheckOut the updated versions for this project
### Previous Versions:
- [SpringBoot_MongoDB](https://github.com/vardhmanhundia/ServerIndexing_springBot)
- [Server Index Swagg UI](https://github.com/vardhmanhundia/Server_SwaggUi)
### Futher Versions:
- [Server_Index React App](https://github.com/vardhmanhundia/ServerIndexing_ReactApp)

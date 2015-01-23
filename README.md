# AirNote - Create Notes Seamlessly 


### Software You Need to Install
* Java JDK8.
* Gradle 2.1
* [NPM](https://www.npmjs.org/)
* NodeJS 0.10.31
* [MongoDB](http://www.mongodb.org/downloads)- Document Oriented DB.

###Project Structure:

 * application- Folder containing the NodeJS Frontend 
 * services-Folder containing Java Backend Services.
 
### Sharing your changes- Using Git to collaborate
 * How do I Learn git ?
 It's simple silly, Play this [game](https://try.github.io/levels/1/challenges/1)

###Running NodeJS application

```shell
> npm install
> npm start
```
Then goto [localhost:3000](http://localhost:3000) for Airnote application.

###Running the Java Backend Services
* Make Sure you have MongoDB instance running locally before you execute the build, this is required for Integration tests to succeed.

```java
> gradle build
> gradle run
```
Then goto [localhost:8080](http://localhost:8080) for services.

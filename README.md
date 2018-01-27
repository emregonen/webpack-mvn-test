# webpack-mvn-test

webpack & spring-boot project with multiple maven modules basen on example by Justin Calleja

BUILD:
in terminal, in parent directory:
  mvn clean install
  //this prıduces the complete jar of project
to Run:
in terminal, in project root directory:
  java -jar ./be/target/be-0.0.1-SNAPSHOT.jar --spring.profiles.active=prod
  
-------------------------------------------------------------------------------
DEVELOPE:
in terminal, in fe directory:
  npm run watch
  //this starts webpack-dev-server with --inline and --hot
in IDE run App.java which contains main method.
//this starts sprint boot application

Browser:
http://localhost:8090/index.html

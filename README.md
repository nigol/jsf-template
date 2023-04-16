# jsf-template
Template for JSF (Jakarta EE) based applications.

## Build and run
Assuming you have Docker available on your development machine, you can use the following command to buil and run project on Tomee application server:

```
sudo docker run -it --rm --name my-maven-project -v "$(pwd)":/usr/src/mymaven -w /usr/src/mymaven -p 8080:8080 -v maven-repo:/root/.m2 maven:3.9-amazoncorretto-20-debian-bullseye mvn install tomee:run
```

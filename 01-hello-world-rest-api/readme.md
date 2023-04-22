# Hello World Rest API

### Running the Application

Run com.in28minutes.rest.webservices.restfulwebservices.RestfulWebServicesApplication as a Java Application.

- http://localhost:8080/hello-world

```txt
Hello World V1 abcde
```

- http://localhost:8080/hello-world-bean

```json
{"message":"Hello World"}
```

- http://localhost:8080/hello-world/path-variable/in28minutes

```json
{"message":"Hello World, in28minutes"}

```

You can build an image with the above configurations by running this command.

mvn clean package dockerfile:build
mvn clean package dockerfile:push

```
session affinity : ClinetIP OR None 

watch -n 0.001 "curl 'http://34.30.105.150:8080/hello-world'"


```


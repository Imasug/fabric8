##### Create docker image

The image is stored in a local docker repository.

```
mvn package fabric8:build
```

##### Run a container of the created docker image

```
docker run -it -p 8080:8080 --rm sample/fabric8
```

##### See
- [fabric8-maven-plugin](https://maven.fabric8.io/)
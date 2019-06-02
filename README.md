
## Package & Build Docker Image

### By Maven

```
$ mvn package -Dmaven.test.skip=true

$ mvn install dockerfile:build -Dmaven.test.skip=true
```

### Or by Gladle

```
$ ./gradlew build

$ ./gradlew build docker
```

## Run It

```
$ java -jar build/libs/spring-boot-docker-0.1.0.jar
```
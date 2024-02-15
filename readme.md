This is the Dockerized version of https://github.com/Ruslan-Aliyev/Spring-Boot-CRUD

1/ Build the `jar`: https://github.com/Ruslan-Aliyev/Spring-Boot-CRUD?tab=readme-ov-file#package-into-jar

2/ Write just the `Dockerfile`, then test
```
docker build --tag=spring-boot-docker .
docker run -p 8080:8080 spring-boot-docker
```

3/ Finish the `docker-compose.yml`, then test:
```
docker-compose build # For rebuild, append --no-cache
docker-compose up
```

4/ Visit http://localhost:8080/api/v1/student ; Test CRUDs https://github.com/Ruslan-Aliyev/Spring-Boot-CRUD?tab=readme-ov-file#crud and see PGAdmin on http://localhost:5000

![Screenshot 2024-02-15 102453](https://github.com/Ruslan-Aliyev/Spring-Boot-CRUD_Dockerized/assets/6761422/80b13bb9-f475-4948-81cc-4953625eb14c)

## Tutorials

- https://www.baeldung.com/dockerizing-spring-boot-application
- https://springhow.com/spring-boot-and-postgres-using-docker-compose/

Clonar Repo para prueba


# docker-java


## docker-normal-build-demo

To build the image:

```shell
$ cd docker-java
$ docker build -t npalavecino/xxx:1.0 .
$ docker images ls | grep npalavecino/xxx:1.0
$ docker run -d -p 8080:8080 npalavecino/xxx:1.0   

En Navegador web  probar: 
http://localhost:8080/

En CLI:
$ curl http://localhost:8080/



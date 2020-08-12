#using alpine image
FROM frolvlad/alpine-java

WORKDIR /app

ADD spring-petclinic-rest /app/spring-petclinic-rest

WORKDIR /app/spring-petclinic-rest

RUN ls -art

CMD ["/app/spring-petclinic-rest/mvnw","spring-boot:run"]
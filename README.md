<<<<<<< HEAD
# campus-placement-secured
you will need to create a new spring boot project with the following spring dependencies selected :
Lombok, Spring data jpa,mysql , spring security, Spring dev tools, spring web tools and validation

add the following in the application.properties


----------------------------------------------------------------
#Default embedded Tomcat server port number 8080

#server.port=7070 can uncomment this to make custom port for your server

#context path default value : empty
#server.servlet.context-path=/
#DB properties
spring.datasource.url=jdbc:mysql://localhost:3306/project?useSSL=false&allowPublicKeyRetrieval=true

spring.datasource.username=your mysql username

spring.datasource.password=your mysql password

#JPA properties

spring.jpa.show-sql = true

spring.jpa.hibernate.ddl-auto = update


#for multipart file handling

spring.servlet.multipart.max-file-size=1MB file size limit according to you

spring.servlet.multipart.max-request-size=1MB file size limit according to you

spring.servlet.multipart.enabled=true

spring.servlet.multipart.location=${java.io.tmpdir} will save the recieved files here but has logic to transfer to a readable location

#springsecurity 

jwt.secret=your secret key

jwt.jwtExpirationInMs=expiration time for the key


---------------------------------------------------

look for whitespaces in appilcation.properties and remove them
=======
# CampusPlaceMentBackEnD
>>>>>>> 2ab8f0e7579c258fe65f39a81858d01edf34b7c3

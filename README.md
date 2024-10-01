# Product Service
A Spring Boot Application written in Kotlin uses Spring ACL to provide fine-grained access at the Record Level. For Example, only the seller who added the product can edit it, he cannot edit products added by other sellers

Technologies Used
* Kotlin
* Gradle
* Spring ACL
* Spring Boot
* Spring Security
* Simple JWT Token Based Authentication and Authorization
* PostgreSQL DB
* RBAC

# Setup
* Install PostgreSQL; you can install it from official website https://www.postgresql.org/download/ OR install via Docker
* Go to /src/main/resources/application.properties
* Replace the <port> in  <b>jdbc:postgresql://localhost:<i><b><<port>port></b></i>/<database_name></b>  with the port of your PostgreSQL and <b><i><database_name></i></b> with your own database name
* Run using <b>ProductserviceApplication.kt</b>

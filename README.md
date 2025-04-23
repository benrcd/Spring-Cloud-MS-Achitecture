![img.png](img.png)


### 📦 spring-boot-starter-actuator
* Purpose: Exposes production-ready endpoints (health checks, metrics, etc.).
* Use case: Enables monitoring tools like Prometheus, shows app status at /actuator/*.

### 📦 spring-boot-starter-data-jpa
* Purpose: Integrates Spring Data with JPA (usually Hibernate).
* Use case: Simplifies database interactions via repositories and ORM mapping.

### 📦 spring-boot-starter-data-rest
* Purpose: Automatically exposes JPA repositories as REST endpoints.
* Use case: Quickly turn your repository methods into a REST API without writing controllers.

### ☁️ spring-cloud-starter-config
* Purpose: Connects your microservice to a centralized Spring Cloud Config Server.
* Use case: Externalizes configuration (like application.yml) so you can manage it remotely.

### ☁️ spring-cloud-starter-netflix-eureka-client
* Purpose: Registers your microservice with a Eureka Discovery Server.
* Use case: Enables service discovery — other services can find and communicate with it by name instead of hardcoded URLs.
In brief, this demo project includes three components:

1. **Eureka Server**:
   - Acts as a **service registry** for microservices.
   - Other services (like User and Order Service) can register themselves with Eureka, and Eureka helps them discover each other.

2. **User Service**:
   - A simple REST service exposing an endpoint (`/users`) to simulate user-related operations.
   - Registers itself with Eureka for service discovery.

3. **Order Service**:
   - A simple REST service exposing an endpoint (`/orders`) to simulate order-related operations.
   - Registers itself with Eureka for service discovery.

The project demonstrates how **Spring Cloud Eureka** helps microservices discover each other in a distributed system.

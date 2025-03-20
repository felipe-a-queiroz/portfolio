# Simplified E-commerce Platform

This project demonstrates the implementation of a simplified e-commerce platform using microservices, Spring Boot, Java 17+, and various modern technologies.

## Features

* **Catalog:**
    * Product and category registration and management.
    * Product search by name, category, and price.
* **Shopping Cart:**
    * Adding and removing products from the cart.
    * Shopping cart visualization.
* **Orders:**
    * Order processing and checkout.
    * User order history.
* **Users:**
    * User registration and authentication.
    * User profile management.
* **Payments (Simulated):**
    * Simulated payment processing.
* **Coupons:**
    * Discount coupon management.

## Architecture

This project uses a microservices architecture, with the following services:

* **Catalog Service:** Spring Boot, MySQL, Redis.
* **Shopping Cart Service:** Spring Boot, Cassandra, Redis.
* **Orders Service:** Spring Boot, PostgreSQL.
* **Users Service:** Spring Boot, MySQL, JWT.
* **Payments Service (Simulated):** Spring Boot.
* **API Gateway:** Spring Cloud Gateway.

Communication between services is done through RESTful APIs and message queues (RabbitMQ or Kafka).

## Technologies

* **Back-end:**
    * Java 17+
    * Spring Boot
    * Spring Data JPA
    * Spring Security (JWT)
    * Spring Cloud Gateway.
* **Databases:**
    * MySQL (Catalog, Users)
    * Cassandra (Shopping Cart)
    * PostgreSQL (Orders)
* **Cache:**
    * Redis
* **Message Queues:**
    * RabbitMQ
* **API:**
    * RESTful
    * OpenAPI (Swagger) documentation.
* **DevOps:**
    * Docker
    * Kubernetes

## How to Run

1.  Clone the repository.
2.  Make sure you have Docker installed.
3.  Run `docker-compose up` at the project root.
4.  Access the API documentation at `http://localhost:8080/swagger-ui.html`.

## Contribution

Contributions are welcome! Feel free to open issues and pull requests.

## License

This project is licensed under the GPLv3 license. See the [LICENSE](LICENSE) file for more information.

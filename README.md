# Ecommerce Microservices Platform

This project demonstrates a microservices-based ecommerce backend built using **Spring Boot**.

## Services

- Product Service

## Technologies Used

- Java 17
- Spring Boot
- Spring Data JPA
- H2 Database
- Maven
- REST APIs

## API Endpoints

### Create Product
POST /products

Example Request Body:

{
  "name": "Laptop",
  "price": 1200
}

### Get All Products
GET /products

## How to Run the Project

1. Clone the repository

git clone https://github.com/Richarreddy123/ecommerce-microservices-platform.git

2. Navigate to the project folder

cd ecommerce-microservices-platform/product-service

3. Run the application

mvn spring-boot:run

4. Access API

http://localhost:8080/products

## Author

Richa Reddy

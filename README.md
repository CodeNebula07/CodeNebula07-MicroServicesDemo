# MICROSERVICES PROJECT

# Microservices User Rating and Hotel

This project demonstrates the implementation of three microservices - User Rating, Hotel, and Eureka Server - using Java Spring Boot. The microservices are connected and registered using the Eureka Server for service discovery and communication.

## Microservices Overview

- **User Rating**: This microservice handles user ratings for hotels. Users can submit ratings and retrieve the average rating for a specific hotel.
- **Hotel**: This microservice manages hotel information. It provides APIs to retrieve hotel details and update hotel information.
- **Eureka Server**: The Eureka Server acts as a service registry and discovery server. It allows microservices to register and discover each other using service names.

## Prerequisites

Make sure you have the following installed:

- Java Development Kit (JDK) 8 or above
- Apache Maven
- Postman

## API Documentation

The microservices provide the following APIs:

- User Rating Microservice:
  - `POST /rating`: Submit a user rating for a hotel.
  - `GET /rating/{hotelId}`: Retrieve the average rating for a specific hotel.

- Hotel Microservice:
  - `GET /hotel/{hotelId}`: Retrieve hotel details for a specific hotel.
  - `PUT /hotel/{hotelId}`: Update hotel information for a specific hotel.

Please refer to the individual microservice documentation for detailed API specifications.

## License

This project is licensed under the [MIT License](LICENSE).

---

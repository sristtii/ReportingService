## ReportingService

A Spring Boot-based Reporting Service that handles credit card reporting functionality. This service integrates with Kafka for event-driven architecture and provides REST APIs for creating and retrieving credit card reports. 

### Features

- **Create Credit Card Reports (POST API)**: Allows the creation of credit card reports
- **Retrieve Credit Card Reports (GET APIs)**:
  - **Get All Reports**: Fetches all reports with pagination and sorting.
  - **Get Report by Transaction ID**: Retrieves a specific report by its unique transaction ID.
- **Kafka Integration**: Consumes messages from the POST API and processes them using an event-driven approach.
- **Database**: Integrates with PostgreSQL to store and manage credit card reports.

### Technologies Used

- **Spring Boot**: Framework for building the REST API.
- **PostgreSQL**: Database for storing credit card reports.
- **Kafka**: Messaging system for event-driven architecture.
- **MapStruct**: For mapping between DTOs and entities.
- **Lombok**: For reducing boilerplate code.

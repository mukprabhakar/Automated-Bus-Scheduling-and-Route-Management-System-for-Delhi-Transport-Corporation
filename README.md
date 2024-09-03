# Automated Bus Scheduling and Route Management System

## Introduction

The Automated Bus Scheduling and Route Management System is designed to enhance the efficiency of bus scheduling and route planning for the Delhi Transport Corporation (DTC). By leveraging advanced algorithms, data analytics, and Geographic Information System (GIS) technologies, the system automates key aspects of bus operations, reducing manual effort, errors, and improving service reliability.

## Features

### 1. Linked Duty Scheduling
- Assigns a specific crew to a bus at the start of their duty.
- Ensures crew remains with the bus throughout their shift.
- Manages and monitors crew and bus assignments for improved familiarity and accountability.

### 2. Unlinked Duty Scheduling
- Allows crews to hand over buses to other crew members after completing trips.
- Manages crew rest periods and reassigns them to buses after their rest.

### 3. Route Management
- Maps all existing routes and provides a visual representation of the bus network.
- Enables the creation of new routes while highlighting overlaps with existing routes.
- Optimizes route planning to reduce congestion and enhance service coverage.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/bus-scheduling-system.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd bus-scheduling-system
   ```
3. **Install dependencies:**
   ```bash
   mvn install
   ```
4. **Set up the database:**
   - Configure your database settings in `application.properties`.
   - Run the database migrations.
   ```bash
   mvn flyway:migrate
   ```

5. **Build and run the application:**
   ```bash
   mvn spring-boot:run
   ```

## Usage

1. **Access the system via a web browser:**
   - Visit `http://localhost:8080` to use the system's interface.

2. **Managing Schedules:**
   - Use the Scheduling module to assign linked or unlinked duties to bus crews.

3. **Managing Routes:**
   - Use the Route Management module to visualize, create, and optimize bus routes.

4. **Accessing Reports:**
   - Generate and view real-time reports on bus schedules and route efficiency.

## Technologies Used

- **Java** (Spring Boot Framework)
- **MySQL** (Database)
- **Thymeleaf** (Template Engine)
- **GIS** (Geographic Information System)
- **Maven** (Dependency Management)

## Contributing

1. Fork the repository.
2. Create your feature branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or support, please contact Mukesh Pal at [mukesh.mmp1234@gmail.com](mailto:mukesh.mmp1234@gmail.com).

---


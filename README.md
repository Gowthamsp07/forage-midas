JPMorgan Chase & Co. – Virtual Internship (Job Simulation)
📌 Overview

This repository contains my work completed as part of the JPMorgan Chase & Co. Virtual Internship / Job Simulation program.
The program is designed to simulate real-world software engineering tasks commonly performed at JPMorgan Chase, with a strong focus on backend development, system integration, and financial transaction handling.

Throughout this internship, I worked on implementing backend components, integrating messaging systems, and understanding how enterprise-grade applications handle large-scale financial data.

🏦 Organization

JPMorgan Chase & Co.
Global Financial Services Company

🎯 Internship Objective

The primary goal of this virtual internship was to:

Gain hands-on experience with enterprise backend systems

Understand real-time transaction processing

Work with Kafka-based messaging systems

Apply Spring Boot concepts in a production-style project

Follow industry-standard coding and configuration practices

🛠️ Tech Stack Used

Java

Spring Boot

Apache Kafka

YAML Configuration (application.yml)

Maven

RESTful Architecture

Git & GitHub

📂 Project Structure (High-Level)
midas-core/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/jpmorgan/midas/
│   │   │       ├── config/
│   │   │       ├── kafka/
│   │   │       ├── model/
│   │   │       ├── service/
│   │   │       └── MidasCoreApplication.java
│   │   │
│   │   └── resources/
│   │       └── application.yml
│   │
│   └── test/
│
├── pom.xml
└── README.md

📌 Tasks Completed
✅ Task 1: Kafka Integration

Integrated Apache Kafka into the Midas Core application

Used configuration values from application.yml to dynamically select Kafka topics

✅ Task 2: Kafka Listener Implementation

Implemented a Kafka Listener to listen for incoming transaction messages

Ensured messages are correctly consumed from the configured topic

✅ Task 3: Message Deserialization

Deserialized incoming Kafka messages into the provided Transaction model

Ensured data integrity and correct object mapping

✅ Task 4: Backend Processing

Connected Kafka events to backend services

Prepared the system for real-time transaction handling

🧠 Key Learnings

How large financial systems process transactions asynchronously

Real-world usage of Kafka consumers in enterprise systems

Importance of configuration-driven development

Clean separation of concerns in backend architecture

Writing scalable and maintainable Spring Boot applications

🚀 How to Run the Project

Clone the repository

git clone <repository-url>


Navigate to the project directory

cd midas-core


Build the project

mvn clean install


Run the application

mvn spring-boot:run


⚠️ Note: Kafka and required brokers must be running for full functionality.

📈 Outcome

By completing this virtual internship, I gained practical exposure to enterprise backend development, improved my understanding of financial systems, and strengthened my skills in Spring Boot and Kafka integration, aligning closely with real software engineering roles at JPMorgan Chase.

📜 Certification

This project was completed as part of the JPMorgan Chase & Co. Virtual Internship / Job Simulation Program.

👤 Author

Gowtham SP
Computer Science Engineering (AIML)
Aspiring Software Engineer....

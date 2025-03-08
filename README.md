📚 "Books and Authors" Microservices with Kafka Events


📝 Overview

This project consists of multiple microservices that work together using Kafka. 
The Books Publisher Service publishes a new book every 20 seconds by creating an event and sending it to a Kafka topic. 
The persistence services consume the necessary information and store it.


🚀 Services Used

Books Publisher Service – Generates and publishes books to Kafka.

Books Persistence Service – Consumes book events and stores book data.

Authors Persistence Service – Processes and stores author-related information.

Notification Service – Saves notifications based on book events.


🛠️ Technologies

Spring Boot (Microservices)

Kafka (Event Streaming)

Docker & Docker Compose (Containerization)

H2 (Database for persistence services)


▶️ How to Run

Clone the repository:

Start the services using Docker Compose:

docker-compose up

Verify that Kafka and microservices are running.


📂 Project Structure

📦 books-microservices<br>
├── 📂 books-publisher-service<br>
├── 📂 books-persistence-service<br>
├── 📂 authors-persistence-service<br>
├── 📂 notification-service<br>
├── 📜 docker-compose.yml<br>
├── 📜 README.md<br>

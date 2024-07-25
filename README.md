# Chat Room Application

## Introduction

This project is a simple Chat Room application built with Spring Boot and WebSocket. Users can join the chat room and send messages in real time.

## Features

- Real-time messaging using WebSocket
- Simple and intuitive user interface
- Multiple users can join the chat room

## Technologies Used

- Spring Boot
- Spring WebSocket
- HTML/CSS/JavaScript

## Getting Started

### Prerequisites

- Java 8 or higher
- Maven

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/chat-room-application.git
    cd chat-room-application
    ```

2. Build the project using Maven:

    ```bash
    mvn clean install
    ```

3. Run the application:

    ```bash
    mvn spring-boot:run
    ```

4. Open your web browser and go to `http://localhost:9090`.

## Project Structure

- **src/main/java/com/chatApp/chatRoomApp**: Contains the Java source code.
  - **controller**: Contains the WebSocket controller.
  - **model**: Contains the message model.
  - **config**: Contains the WebSocket configuration.
- **src/main/resources/static**: Contains static resources like CSS and JavaScript files.

## Usage

1. Open `http://localhost:9090` in multiple browser tabs or different browsers to simulate multiple users.
2. Enter a username and join the chat room.
3. Start sending messages in real-time.


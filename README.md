# real-time-chat-application
A real-time chat application built using Spring Boot, WebSocket, STOMP, HTML, CSS, and JavaScript to enable instant communication between multiple users. The application allows users to send and receive messages in real time without refreshing the page, providing a smooth and interactive chatting experience.

The backend is developed with Spring Boot and uses WebSocket with the STOMP messaging protocol to establish persistent, bidirectional communication between the server and connected clients. The frontend is designed using HTML, CSS, and JavaScript to create a clean, responsive, and user-friendly interface. Messages are delivered instantly to all connected users through real-time broadcasting.

This project demonstrates key concepts of event-driven architecture, client-server communication, WebSocket integration, and real-time data exchange. It also showcases the implementation of RESTful APIs, dependency management using Maven, and the development of scalable web applications with Spring Boot.

Key Features -
Real-time messaging using WebSocket,
STOMP protocol for efficient message exchange,
Multi-user chat support,
Instant message broadcasting,
Responsive and user-friendly interface,
Spring Boot-based backend,
Maven for dependency management

Technologies Used-
Java,
Spring Boot,
Spring WebSocket,
STOMP,
HTML5,
CSS3,
JavaScript,
Maven,


+-------------------+
|      Client       |
| HTML, CSS, JS     |
+---------+---------+
          |
          | WebSocket (STOMP)
          |
+---------v---------+
|   Spring Boot     |
|  WebSocket Server |
+---------+---------+
          |
          | Message Broadcast
          |
+---------v---------+
| Connected Clients |
| User 1 | User 2   |
| User 3 | User N   |
+-------------------+

Project Status: Successfully developed and tested in a local development environment. Deployment to a cloud platform has not been implemented yet.

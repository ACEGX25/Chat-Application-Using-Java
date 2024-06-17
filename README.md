# Chat Application Using Java

This repository contains an online chat application developed using Spring Boot. Follow the steps below to set up and run the application.

## Getting Started

### Prerequisites

- Java Development Kit (JDK)
- Maven
- A text editor or an IDE (such as IntelliJ IDEA or Eclipse)

### Installation

1. **Visit Spring Initializr**
   - Go to [Spring Initializr](https://start.spring.io/).
   - Select the following options:
     - **Project**: Maven
     - **Language**: Java
     - **Spring Boot Version**: Choose the desired stable version
     - **Packaging**: Jar
     - **Java Version**: Select the version you have installed
     - **Dependencies**: Add "WebSocket"

2. **Generate the Project**
   - Click on "Generate" to download the project as a ZIP file.
   - Extract the ZIP file to your desired location.

### Configuration

1. **Set the Port**
   - Change to your desired port in the `application.properties` file located in the `src/main/resources` folder.
     ```properties
     server.port=8080
     ```

### Implementation Details

1. **MessageController**
   - Created in the `java` folder to handle message mapping and sending messages to all connected clients.

2. **Messages**
   - Created in the same way to specify the name and content, along with their getter and setter methods.

3. **Configuration**
   - Added configuration file to use STOMP and message broker properties.

### Frontend

- In the `static` folder, added a simple frontend with HTML, CSS, and JavaScript.
- Feel free to modify the frontend as per your needs.

### Collaboration

This project was created by `ACEGX25` along with `ashutoshh-17`.

For a detailed explanation, watch this video: [Watch Here](https://youtu.be/bBQnWcbxDo8?si=GCsmmGF-DoBr93ta)

Feel free to fork this repository and contribute to the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Happy coding!

##SCREENSHOTS
![Screenshot 2024-06-17 173109](https://github.com/ACEGX25/Chat-Application-Using-Java/assets/143728245/b6043a08-264b-4285-aa7c-162ab94ef81c)
![Screenshot 2024-06-17 173144](https://github.com/ACEGX25/Chat-Application-Using-Java/assets/143728245/4c090246-cd82-4108-b8fa-dec069bccec3)
![Screenshot 2024-06-17 173219](https://github.com/ACEGX25/Chat-Application-Using-Java/assets/143728245/d79289b8-4cef-42e5-b120-0885423cff66)
![Screenshot 2024-06-17 173240](https://github.com/ACEGX25/Chat-Application-Using-Java/assets/143728245/0c1132e8-d6d8-4fa0-bd2c-d9629864863b)



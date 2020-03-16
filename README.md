# nd035-chatroom-project
This is Chat Room project for Udacity Java Developer Nanodegree (nd035).

This project requires Udacity nd035 students to implement a web-based Chat Room application.
It is implemented using **WebSocket API**. It also uses **Thymeleaf template engine** for rendering UI. 

## Tools Required
1. Spring Boot Framework
2. Maven Plug-in configured with your IDE

## How To Run
1. mvn clean package
2. mvn spring-boot:run **0r** java -jar target/chatroom-starter-0.0.1-SNAPSHOT.jar

## Usage / Testing
1. Open a web browser
2. Hit url http://localhost:8080/
3. Enter your username
4. Click on Login button 
5. You join the chat room
6. To be able to test the app, typically, you'll want to login with different usernames in different 
   browser tabs while the web app is running.
6. It will show Online Users count on right-top corner and message sent from any user will be braodcasted 
   to all online users at the moment.

## License
This project uses MIT License. Please read [LICENSE](https://github.com/kalyani7t/nd035-chatroom-project/blob/master/LICENSE) under this project before using it.


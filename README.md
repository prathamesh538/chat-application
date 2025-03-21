# chat-application

*COMPANY*:CODTECH IT SOLUTIONS

*NAME*:PRATHAMESH SANJAY PATHARE

*INTERN ID*:CT08WPS

*DOMAIN*:JAVA PROGRAMMING

*DURATION*:4 WEEKS

*MENTOR*:NEELA SANTOSH KUMAR

### **Description of a Simple Chat Application Using Java JFrame and Swing Components**  

#### **Overview**  
This simple chat application is built using **Java JFrame** and **Swing components** in **NetBeans**. The application allows real-time messaging between a **client** and a **server** using **sockets** in Java. The user interface includes a **JTextArea** to display messages, a **JTextField** for user input, and a **JButton** to send messages.  

#### **Technologies Used**  
- **Java (JDK 8 or later)**  
- **Swing (JFrame, JTextArea, JTextField, JButton, JScrollPane, etc.)**  
- **Java Networking (Socket, ServerSocket)**  
- **NetBeans IDE**  

#### **Features**  
1. **Client-Server Communication**: Messages are sent from the client to the server and displayed in the chat window.  
2. **Graphical User Interface (GUI)**:  
   - **JTextArea**: Displays the conversation.  
   - **JTextField**: Allows the user to type messages.  
   - **JButton**: Sends messages when clicked.  
   - **JScrollPane**: Adds scroll functionality to the chat area.  
3. **Multi-threading**: The server handles multiple client connections.  
4. **Simple and Easy to Use**: The interface is user-friendly.  

#### **Implementation Details**  
1. **Server Side (ChatServer.java)**  
   - Uses `ServerSocket` to listen for client connections.  
   - Receives messages from clients and broadcasts them.  

2. **Client Side (ChatClient.java)**  
   - Connects to the server using `Socket`.  
   - Sends and receives messages, updating the chat area dynamically.  

*output:
![image](https://github.com/user-attachments/assets/1e98352d-fd67-4d0c-b80c-ee02b50ece60)


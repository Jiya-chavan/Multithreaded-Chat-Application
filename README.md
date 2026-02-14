# Multithreaded-Chat-Application

Company: CODTECH IT SOLUTIONS

Name: JIYA CHAVAN

Intern ID: CTIS2990

Domain: Java Programming

Duration: 4 weeks

Mentor: Neela Santosh

I built a multithreaded client–server chat application using Java to understand how real-time communication systems work over computer networks. The application was developed using Java socket programming concepts, where I created a dedicated server program and multiple client programs that communicate through network sockets. The server was responsible for listening to incoming client requests on a specific port using the ServerSocket class, while each client connected to the server using the Socket class by providing the server’s IP address and port number. Once a connection was established, the server accepted client requests and created a separate thread for each connected client, enabling multiple users to communicate simultaneously without interrupting one another. I implemented multithreading by creating a ClientHandler class that implemented the Runnable interface (or extended the Thread class), allowing each client to run on an independent thread. This ensured that messages from different clients could be processed concurrently, improving performance and responsiveness. The server maintained a list of active client connections and broadcasted incoming messages from one client to all other connected clients, enabling real-time group communication similar to modern chat applications. For sending and receiving messages, I used input and output streams such as BufferedReader, InputStreamReader, and PrintWriter to efficiently handle text-based communication between the server and clients. Proper synchronization and error handling mechanisms were implemented to manage issues such as client disconnections, I/O exceptions, and unexpected network errors, ensuring the server remained stable even when multiple users connected or disconnected dynamically. Through this project, I gained a deep understanding of how data is transmitted over TCP/IP protocols, how sockets establish reliable connections between devices, and how concurrency is handled in real-world applications. I also learned the importance of thread management, resource allocation, and handling shared data structures in a multithreaded environment. The application demonstrated how scalable communication systems are designed, where a single server can manage multiple clients efficiently using concurrent programming techniques. Additionally, this project improved my debugging skills, as I needed to monitor server logs, handle blocked threads, and ensure smooth message broadcasting among users. Building this chat application provided practical exposure to networking fundamentals, including port numbers, IP addressing, and client-server architecture, while also strengthening my understanding of Java’s concurrency model. Overall, this multithreaded chat application enhanced my hands-on experience in socket programming and multithreading, helping me understand how messaging platforms, collaboration tools, and real-time communication systems are implemented at a foundational level using Java.

Output:



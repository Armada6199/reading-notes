# Web Sockets

## What is a Web Socket?

### A Web Socket is a communication protocol that enables real-time, bidirectional data exchange between a client and a server over a  single TCP connection

### Web Socket Request/Response Handshake and Connection Establishment The Web Socket handshake follows the HTTP protocol. The client sends an HTTP request to the server indicating its intent to establish a Web Socket connection. If the server accepts, it responds with an HTTP 101 status code, and the connection is established

### Web Sockets and Content Delivery Web Sockets allow the server to send content to the client without waiting for a request. This enables server-side push mechanisms, making them suitable for real-time applications

# Socket.IO

## What does the event handler io.on() do?

#### he event handler io.on() in Socket.IO listens for incoming events from clients. It allows the server to handle events triggered by clients, such as connection or custom events.

### Possible Proof of Life or Proof of Expected Code Behavior
To verify the code's expected behavior:

Connection Logging: Log client connections using io.on('connection', callback).

Event Triggering: Test event communication by using socket.emit() on the client side and handling events on the server side with io.on().

Data Exchange: Validate data exchange between client and server using socket.emit() and io.on().

Disconnection Handling: Implement disconnection handling with io.on('disconnect', callback) and test different disconnection scenarios.

### What does socket.emit() do?

socket.emit() sends events from the client to the server or from the server to a specific client. It enables bidirectional event-based communication.

On the client side, it sends a specific event with optional data to the server. On the server side, it targets specific clients by referencing their socket ID to send custom events or data.
# CN-TCP-Socket

## CCD Lab Assignment

This project demonstrates **TCP Socket Programming in Python** using client-server communication.

It contains:
- Basic TCP client-server communication
- TCP-based mathematical operations

## Files

```text
CN-TCP-Socket/
│
├── server.py
├── client.py
├── server_math.py
├── client_math.py
└── README.md
```

## How to Run

### 1. Basic TCP Communication

Open **two terminals** in the same folder.

**Terminal 1 — Start the Server:**

```bash
python server.py
```

**Terminal 2 — Start the Client:**

```bash
python client.py
```

The client can then send a message to the server, and the server can send a reply back.

### 2. TCP Calculator

Open **two terminals** in the same folder.

**Terminal 1 — Start the Math Server:**

```bash
python server_math.py
```

**Terminal 2 — Start the Math Client:**

```bash
python client_math.py
```

Enter an operation such as:

```text
5 + 3
```

Output:

```text
Result: 8.0
```

The calculator supports:

```text
+
-
*
/
```

## Important

- Always **start the server before the client**.
- Both programs use `127.0.0.1:8080`.
- `127.0.0.1` refers to the local computer.
- The client and server must use the **same port number**.
- Run the client and server in separate terminals.

## Technologies Used

- Python
- Socket Programming
- TCP/IP
- Client-Server Architecture

## Objective

To understand and implement **TCP socket communication** between a client and server, including sending messages and performing mathematical operations over a TCP connection.

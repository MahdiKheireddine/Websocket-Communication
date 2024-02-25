Websocket-Communication
WebSocket is a protocol for machine-to-machine communication that maintains a TCP connection open for bi-directional passing of information. It enables a connection between two computers, allowing them to send and receive information. The WebSocket protocol can be configured as a server or client. A WebSocket server listens for requests and returns results based on the input. Additionally, the server can also function as a client by sending information without a specific request.

Installation
The websockets package is a Python library for building WebSocket servers and clients. You can install it using pip:

pip install websockets

Websocket Server

The Python websockets package is build on top of asyncio for asynchronous actions from the server as it listens for client requests. Create a simple WebSocket server and run the Python script to start the API. The API listens for a name and returns a greeting.

Websocket Client

The websockets client sends a name and listens for a return response.

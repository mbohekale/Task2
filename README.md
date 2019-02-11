# Task2
### The client reads numbers from a file, and sends them to the server.
    After the last number, the client sends the text "end" to the server.
    The server applies the function f(n)=2*n+1 to all numbers,
    and sends them back to the client.
    The client should print the received numbers.
    The same as exercise 2, but after a client has quit,
        the server should wait for another connection.
        Thus, the server never exits: it is always waiting for a client to connect,
        or is communicating with one.

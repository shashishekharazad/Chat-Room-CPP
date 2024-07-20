# Chatroom Application - Linux Based

A cchatroom application using socket programming and multi-threading for concurrent communication.
Implemented communication channels between the server and clients, ensuring seamless message exchange and managed multiple client connections concurrently, enhancing the efficiency of communication within the chatroom.

## How to run

1. Clone this repository
2. Run the following commands in your terminal :
```
g++ server.cpp -lpthread -o server
g++ client.cpp -lpthread -o client
```
3. To run the server application, use this command in the terminal :
```
./server
```

4. Now, open another terminal and use this command to run the client application :
```
./client
```

5. For opening multiple client applications, repeat step 4.
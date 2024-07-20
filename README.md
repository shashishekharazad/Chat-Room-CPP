# Chatroom Application - Linux Based

A chatroom application using socket programming and multi-threading for concurrent communication. Implemented communication channels between the server and clients, ensuring seamless message exchange, managing multiple client connections concurrently, and enhancing communication efficiency within the chatroom.

If you want, you can clone this repository and modify the program.
```
git clone https://github.com/shashishekharazad/Chat-Room-CPP.git
```
## How to run

1. Compile the server and client program :
```
g++ server.cpp -lpthread -o server
g++ client.cpp -lpthread -o client
```
2. Run the server using following command :
```
./server
```

3. Now, open another terminal and run the client application :
```
./client
```

4. To create multiple client, run the client application.

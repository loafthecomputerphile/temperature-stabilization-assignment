# Temperature stabilization using inter-process communication

assignment completed using docker image.
used for loops for continuous communication between client and server.

![execution_image](./execution_image.png) 

#### Compilation:

```shell
gcc utils.c tcp_server.c -o server
gcc -o client tcp_client.c utils.c
```

Commands Used: 

```shell
./server
```  

```shell
./client 1 100
```

```shell
./client 2 200
```

```shell
./client 3 300
```

```shell
./client 4 400
```


all:
	gcc client.c -o client
	gcc proxy-server.c -o proxy-server -lpthread -lsocket
	gcc echo-server.c -o echo-server -lsocket
client:
	gcc client.c -o client
proxy:
	gcc proxy-server.c -o proxy-server -lpthread -lsocket
proxy2:
	gcc proxy-server2.c -o proxy-server2 -lpthread -lsocket
echo:
	gcc echo-server.c -o echo-server -lsocket

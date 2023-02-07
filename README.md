# CIS427PRGM1

Start with downloading 

server.cpp
client.cpp
sqlite3.o
sqlite.h

transfer them over to uofm dearborn files with SSH client (Bitvise)

once you transfer them simply compile the server and clinet like such

g++ client.cpp -o client
g++ server.cpp -std=c++11 -ldl -pthread sqlite3.o -o server

After compile run them using

./server
./client

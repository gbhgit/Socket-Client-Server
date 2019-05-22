CC = g++
CFLAGS = -g -Wall
SRCS += src/client.cpp
PROG = client.o

CFLAGS_CPP= -std=c++11

$(PROG):$(SRCS)
	$(CC) $(CFLAGS_CPP) $(CFLAGS) -o $(PROG) $(SRCS)

clean:
	rm -rf $(PROG)

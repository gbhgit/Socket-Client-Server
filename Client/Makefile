CC = g++
CFLAGS = -g -Wall
SRCS += src/client.cpp
PROG = client.o

CFLAGS_CPP= -std=c++11

OPENCV = `pkg-config --cflags --libs opencv` -pthread #-lsqlite3
LIBS = $(OPENCV)

$(PROG):$(SRCS)
	$(CC) $(CFLAGS_CPP) $(CFLAGS) -o $(PROG) $(SRCS) $(LIBS)

clean:
	rm -rf $(PROG)

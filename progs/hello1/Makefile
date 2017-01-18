CC=gcc
TARGET=hello

all:
	$(CC) -c hello.c
	$(CC) -c main.c
	$(CC) -o $(TARGET) hello.o main.o 

clean:
	rm -f *.o $(TARGET)

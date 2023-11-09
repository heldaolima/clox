CC=gcc
DEPENDENCIES=memory.c chunk.c debug.c value.c vm.c scanner.c compiler.c

all: dependencies
	$(CC) -o main main.c *.o

dependencies:
	$(CC) -c $(DEPENDENCIES)

clean:
	rm -f *.o main

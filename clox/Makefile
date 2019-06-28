CC=gcc

objects = main.o chunk.o memory.o debug.o

clox: $(objects)
	$(CC) -o clox $(objects)

.PHONY: clean
clean:
	rm *.o clox

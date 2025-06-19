CC = g++
CFLAGS = -O2 -static
SRC = src/quicksort.c
BIN = bin/x86/linux/quicksort

all: $(BIN)

$(BIN): $(SRC)
	mkdir -p bin
	$(CC) $(CFLAGS) -o $(BIN) $(SRC)

clean:
	rm -rf bin


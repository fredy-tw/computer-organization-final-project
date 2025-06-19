CC = g++
CFLAGS = -O2 -static
SRC = src/multiply.c
BIN = bin/x86/linux/multiply

all: $(BIN)

$(BIN): $(SRC)
	mkdir -p bin
	$(CC) $(CFLAGS) -o $(BIN) $(SRC)

clean:
	rm -rf bin


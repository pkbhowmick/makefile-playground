BIN = myapp

VERSION = 2.0.1

CC = g

all: build run test


build::
	@echo Building the whole project
	go build -o ${BIN} .

build::
	@echo Checking double colon rule

test: test.o
	@echo This is test1
	cc test.o -o output

test.o: test.c
	@echo This is test2
	cc -c test.c -o test.o

test.c:
	echo "int main() {return 0;}" > test.c

run:
	@echo Running the binary
	./${BIN}


clean:
	rm ${BIN}
	rm *.o
	rm test.c



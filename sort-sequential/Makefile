default: build

build:
	gcc main.c -o main.o -std=c99

run: build
	./main.o ${ARRAY_SIZE} ${NUMBER_VECTORS} ${DEBUG}

test: build 
	./main.o

# make
# make run ARRAY_SIZE=10 NUMBER_VECTORS=10 DEBUG=1
# make run ARRAY_SIZE=10 NUMBER_VECTORS=10 DEBUG=0
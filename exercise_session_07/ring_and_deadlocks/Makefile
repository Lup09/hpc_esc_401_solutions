CFLAGS=-O3 -ffast-math -mavx2
CC=mpicc

all: ring

ring: ring.c
	${CC} ${CFLAGS} -o ring ring.c
clean: 
	rm -f ring

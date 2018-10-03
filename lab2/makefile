CC = gcc
CFLAGS = -g -Wall -lpthread

EXECS =  lab2part1 lab2part2 lab2part3 lab2part4 lab2part5

all: ${EXECS}

lab2part1: lab2part1.c
	$(CC) $(CFLAGS) $< -o $@
lab2part2: lab2part2.c
	$(CC) $(CFLAGS) $< -o $@
lab2part3: lab2part3.c
	$(CC) $(CFLAGS) $< -o $@
lab2part4: lab2part4.c
	$(CC) $(CFLAGS) $< -o $@
lab2part5: lab2part5.c
	$(CC) $(CFLAGS) $< -o $@


clean:
	rm $(EXECS)


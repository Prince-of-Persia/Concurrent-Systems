MPICC = mpicc
MPIFLAGS = -g -Wall

EXECS = lab1part1 lab1part2 lab1part3 lab1part4 lab1part5

all: ${EXECS}

lab1part1: lab1part1.c
	$(MPICC) $(MPIFLAGS) $< -o $@

lab1part2: lab1part2.c
	$(MPICC) $(MPIFLAGS) $< -o $@

lab1part3: lab1part3.c
	$(MPICC) $(MPIFLAGS) $< -o $@

lab1part4: lab1part4.c
	$(MPICC) $(MPIFLAGS) $< -o $@

lab1part5: lab1part5.c
	$(MPICC) $(MPIFLAGS) $< -o $@


clean:
	rm $(EXECS)


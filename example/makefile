MPICC = mpicc
MPIFLAGS = -g -Wall

EXECS = hello

all: ${EXECS}


hello: hello.c
	$(MPICC) $(MPIFLAGS) $< -o $@


clean:
	rm $(EXECS)

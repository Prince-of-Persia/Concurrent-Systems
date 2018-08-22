MPICC = mpicc
MPIFLAGS = -g -Wall

EXECS = hello

all: ${EXECS}


hello: hello.c
	$(MPICC) $(MPIFLAGS) -c $< -o $@


clean:
	rm $(EXECS)

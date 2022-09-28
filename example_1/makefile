
#LINUX
COMMON=-O2 -I../../include -L../../lib -pthread -Wl,-no-as-needed -Wl,-rpath,'$$ORIGIN'/../../lib
LIBS = -lmujoco -lglfw
CC = gcc


ROOT = basic

all:
	$(CC) $(COMMON) basic.cpp $(LIBS) -o $(ROOT)

basic.o:
	$(CC) $(COMMON) -c basic.cpp

clean:
	rm *.o $(ROOT)

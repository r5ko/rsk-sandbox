#
# Makefile 
#

CC = gcc
CFLAGS = -Wall -Werror -g -DDRIVER -std=gnu99

OBJS = test.o 

all: test

test: $(OBJS)
	$(CC) $(CFLAGS) -o test.out $(OBJS)

test.o: test.c test.h

clean:
	rm -f *~ *.o test.out
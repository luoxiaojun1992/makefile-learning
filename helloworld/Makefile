# 宏引用
CC=gcc

helloworld:test.o
	$(CC) -o helloworld test.o

test.o:test.c
	$(CC) -c -o test.o test.c

clean:
	rm -f test.o && rm -f helloworld 


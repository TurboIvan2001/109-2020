all: do-test clear

do-test: a.out
	./a.out

a.out: file.o min_value.o
	gcc -c min_value.c
	gcc -c file.c
	gcc min_value.o file.o -lm

clear:
	rm min_value.o file.o a.out

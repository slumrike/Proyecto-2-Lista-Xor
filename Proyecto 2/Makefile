main : funciones.o main.o 
	gcc -o main main.o funciones.o

funciones.o: funciones.c funciones.h
	gcc -c -o funciones.o funciones.c

main.o: main.c funciones.h
	gcc -c -o main.o main.c

iniciar: 
	./main

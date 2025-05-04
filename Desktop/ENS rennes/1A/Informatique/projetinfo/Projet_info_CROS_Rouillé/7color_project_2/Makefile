FLAGS=-Wall -Werror -g

7color : o/GameState.o
	gcc $(FLAGS) o/GameState.o -o 7color $(LDFLAGS)

o/GameState.o: head/GameState.h src/GameState.c
	gcc $(FLAGS) $(CFLAGS) -c src/GameState.c -o o/GameState.o


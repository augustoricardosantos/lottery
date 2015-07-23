all: pb

pb: pb.o
	gcc -std=c99 -Wall -Wextra -Werror -o pb pb.o

pb.o: pb.c
	gcc -std=c99 -Wall -Wextra -Werror -c pb.c

clean:
	rm pb.o pb output.txt

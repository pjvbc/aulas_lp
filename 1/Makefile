CC = gcc
CFLAGS = -Wall #-Werror -Wextra -pedantic -g -fsanitize=address
LDFLAGS =  #-fsanitize=address
LBLIBS =

SRC = a.c
OBJ = $(SRC:.c=.o)
EXEC = a.exe

all: $(EXEC)

$(EXEC): $(OBJ)
	$(CC) $(LDFLAGS) -o $@ $(OBJ) $(LBLIBS)

clean:
	rm -rf $(OBJ) $(EXEC)
CC=gcc
CC_FLAGS=-O2 -std=c99 -Wall -Wextra -pedantic

.PHONEY: all
all: heat_seq

heat_seq: heat_seq.c
        @$(CC) $(CC_FLAGS) $< -o heat_seq

.PHONEY: clean
clean:
        @rm heat_seq

.PHONEY: run
run: all
        @echo "Sequential:"
        @./heat_seq
        @echo

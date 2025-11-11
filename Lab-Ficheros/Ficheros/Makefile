# =====================================================
# Autor: Andres Loreto Quiros
# Fecha: 4 de Noviembre 2025
# Tema: Ficheros
# Makefile para compilar los laboratorios 01 y 02
# =====================================================

CC = gcc
CFLAGS = -Wall -Wextra -O2
TARGETS = lab01 lab02

all: $(TARGETS)

lab01: lab01.c
	$(CC) $(CFLAGS) lab01.c -o lab01

lab02: lab02.c
	$(CC) $(CFLAGS) lab02.c -o lab02

run1: lab01
	./lab01

run2: lab02
	./lab02

clean:
	rm -f $(TARGETS)

.PHONY: all clean run1 run2
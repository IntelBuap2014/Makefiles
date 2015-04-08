OBJETOS = HolaPiñata.o holafuncion.o

FUENTES = HolaPiñata.c holafuncion.c

CFLAGS = -g -Wall -O3

.PHONY: limpiar

all: enlazar compilar

enlazar: ${FUENTES}
	${CC} -c ${FUENTES}

compilar: ${OBJETOS}
	${CC} ${CFLAGS} -o hola ${OBJETOS}

limpiar:
	rm -f hola ${OBJETOS}

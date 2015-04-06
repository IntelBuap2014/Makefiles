OBJECTOS = HolaPiñata.o holafuncion.o
FUENTES = HolaPiñata.c holafuncion.c

all: enlazar compilar

enlazar: ${FUENTES}
	gcc -c ${FUENTES}

compilar: ${OBJETOS}
	gcc -o hola ${FUENTES}

OBJETOS = HolaPiñata.o holafuncion.o
FUENTES = $(HOME)/../../run/media/wozgeass/f19cb489-882a-4d32-af0a-89154fe93471/home/wozgeass/Repos/MakeFile/Makefiles/Ejemplo4/*.c

CFLAGS = -g -Wall -O3

all: enlazar compilar

enlazar: ${FUENTES}
	${CC} -c ${FUENTES}

compilar: ${OBJETOS}
	${CC} ${CFLAGS} -o hola ${OBJETOS}

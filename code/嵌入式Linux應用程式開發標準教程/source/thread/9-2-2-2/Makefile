EXEC = thread_mutex
OBJS = thread_mutex.o
HEADERS = 

CC = gcc
INC = -I.
CFLAGS = ${INC} -lpthread -g 

all:${EXEC}
${EXEC} : ${OBJS}
	${CC} ${CFLAGS} ${LDFLAGS} -o $@ ${OBJS} 

${OBJS} : ${HEADERS}

.PHONY : clean
clean :
	-rm -f ${OBJS} ${EXEC}


TARGET := ../lib/libindexer.so
SRCS := $(wildcard *.c)
CFLAG := -I ../include

${TARGET} : ${SRCS}
	gcc ${CFLAG} -fPIC -shared $^ -o $@

clean:
	rm ${TARGET}

CXXFLAGS += -I../include

default: libc++fileno.a

clean:
	rm -f libc++fileno.a fileno.o

libc++fileno.a: fileno.o
	ar r "$@" "$<"

fileno.o: fileno.cpp
	g++ ${CXXFLAGS} -c -o "$@" "$<"

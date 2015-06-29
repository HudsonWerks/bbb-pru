CFLAGS+=-Wall -Werror
LDLIBS+= -lpthread -lprussdrv

all: major-tom-pru.bin major-tom-pru

clean:
        rm -f major-tom-pru *.o *.bin

major-tom-pru.bin: major-tom-pru.p
        pasm -b $^

major-tom-pru: major-tom-pru.o

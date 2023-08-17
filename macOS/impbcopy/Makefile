all: impbcopy

impbcopy:
	gcc -Wall -g -O3 -ObjC -framework Foundation -framework AppKit -o impbcopy impbcopy.m

clean:
	rm -rf impbcopy.dSYM

clean-all:
	rm -rf impbcopy impbcopy.dSYM

install: impbcopy clean
	cp impbcopy ~/bin/

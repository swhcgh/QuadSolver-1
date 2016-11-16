FILE = output.c
CUNIT = ../../cunit/cunit.c

main:
	gcc -g -O -c $(FILE)

clean:
	rm -rf *.o test a.out

test:

testrun:
	./test

debug:
	gcc -std=c99 -g test.c $(FILE) $(CUNIT) -lm
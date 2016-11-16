SUBDIRS = qsolv input output formatting validation qs
TESTDIRS = qsolv input formatting
CLEAN = make clean
TEST = make test
OUTPUT = output/output.o
INPUT = input/input.o
FORMAT = formatting/formatting.o
QSOLV = qsolv/qsolv.o
QS = qs/qs.o
VALID = validation/validation.o

all:
	for dir in $(SUBDIRS); do \
		$(MAKE) -C $$dir; \
	done

clean:
	rm -rf qsolver
	for dir in $(SUBDIRS); do \
		$(CLEAN) -C $$dir; \
	done

test:
	for dir in $(TESTDIRS); do \
		$(TEST) -C $$dir; \
	done

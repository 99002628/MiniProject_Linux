all: all.out

all.out: swimlane.o 
	gcc $^ -o $@ -lgtest -lgtest_main -lpthread


swimlane.o:swimlane.c memoryPool.h
	gcc $< -c


clear:
	rm -rf *o *.out

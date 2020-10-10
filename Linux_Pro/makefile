all: all.out

all.out: swimLane.o pellet.o fish.c
	gcc $^ -o $@ -lgtest -lgtest_main -lpthread

clear:
	rm -rf *o *.out

swimLane.o:swimLane.c memoryPool.h
	gcc $< -c

pellet.o:pellet.c memoryPool.h
	gcc $< -c

fish.o:fish.c memoryPool.h
	gcc $< -c

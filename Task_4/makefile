.PHONY: testing, compileTest

compile: main.c source.c
	gcc -o main uzduotis_4.c source.c
	
run:
	main

compileTest: test.c source.c
	gcc -o test test.c source.c

testing:
	test
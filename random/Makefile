all:

first:
	gcc -g First.c -o First

open_1:
	gcc -g open_1.c -o open_1

open_2:
	gcc -g open_2.c -o open_2

open_3:
	gcc -g open_3.c -o open_3

open_4:
	gcc -g open_4.c -o open_4

open_4_temps:
	gcc open_4.c -save-temps

open_5:
	gcc -g open_5.c -o open_5

create_1:
	gcc -g create_1.c -o create_1

create_2: clean
	gcc -g create_2.c -o create_2

CommandLine_1:
	gcc -g CommandLine_1.c -o CommandLine_1

CommandLine_2:
	gcc -g CommandLine_2.c -o CommandLine_2

CommandLine_3: clean
	gcc -g CommandLine_3.c -o CommandLine_3

error_1: clean
	gcc -g error_1.c -o error_1 

error_2: clean
	gcc -g error_2.c -o error_2 

clean:
	rm -rf *.i *.o *.s
	find . -maxdepth 1 -type f -executable -exec rm -f {} +

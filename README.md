Description
It is a interpreter for Monty ByteCodes files.

Usage
Clone the repository:
https://github.com/Lexxyla/monty.git
Enter at directory
cd monty
Compile:
gcc -Wall -Werror -Wextra -pedantic *.c -o monty
Execute:
./monty file.m
//The file contains the bytcode instructions for example
cat -e 000.m
push 0$
push 1$
push 2$
  push 3$
                   pall    $
push 4$
    push 5    $
      push    6        $
pall$
Functions
The functions used are:

Name	Description	Return	File
_f_add	adds the top two elements of the stack	No Return	add.c
addnode	add node to the head stack	No Return	addnode.c
f_div	divides the top two elements of the stack.	No Return	div.c
execute	executes the opcode	No Return	execute.c
free_stack	frees a doubly linked list	No Return	free_stack.c
main	monty code interpreter	0 on success	main.c
Examples
$lexxyla> ls
basics.c    general.c  main.h  memory.c   shell.c
builders.c  helper.c   hsh          README.md  test

Authors Ukachukwu Michael

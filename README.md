This is betty file:

Go to github craete your repository and clone to snabox, gitbash,vscode or whatever unix ur using.
create a new directory mkdir 0x00-hello_world

create  the new files 
FOR TASK 0
touch 0-preprocessor 
#!/bin/bash
gcc -E $CFILE >> c

For Task 1 
touch 1-compiler
#!/bin/bash
gcc -c $CFILE

For Task 2
touch 2-assembler
#!/bin/bash
gcc -S $CFILE

For Task 3
touch 3-name
#!/bin/bash
gcc -o cisfun $CFILE

Now for these first dour files you must run chmod u+x "filename" to make it executable. all the files that do not end with .c


For Task 4
touch 4-puts.c
#include <stdio.h>
/**
 * main - main block
 * Return: 0
 */
int main(void)
{
puts("\"Programming is like building a multilingual puzzle");
return (0);
}

For Task 5
touch 5-printf.c
#include <stdio.h>
/**
 * main - main block
 * Return: 0
 */
int main(void)
{
printf("with proper grammar, but the outcome is a piece of art,\n");
return (0);
}

For Task 6
touch 6-size.c
#include <stdio.h>

/**
 * main - main block
 * Return: 0
 */
 
int main(void)
{
	printf("Size of a char: %i byte(s)\n", sizeof(char));
	printf("Size of an int: %i byte(s)\n", sizeof(int));
	printf("Size of a long int: %i byte(s)\n", sizeof(long int));
	printf("Size of a long long int: %i byte(s)\n", sizeof(long long int));
	printf("Size of a float: %i byte(s)\n", sizeof(float));
	return (0);
}


ADVANCED TASK
For Task 7
touch 100-intel
#!/bin/bash
gcc -S -masm=intel $CFILE


For Task 8
touch 101-quote.c
#include <stdio.h>
#include <unistd.h>
/**
 * main - Entry point
 * Return:1
 */
int main(void)
{
	write(1, "and that piece of art is useful\" - Dora Korpar, 2015-10-19\n", 59);
	return (1);
}


Now for BETTY after cloning Betty and moving to /bin/
touch testBetty.c
#include <stdio.h>

int main(void)
{
int a = 5;
int b = 4;


for (a < b;;)
{
    printf("%d\n", a++);
}
}


git add .
git commit -m "master"
git push origin master

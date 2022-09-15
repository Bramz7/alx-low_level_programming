Based on the main.c file above, create a file named 0-main.c. This file must test that the function positive_or_negative() gives the correct output when given a case of 0.



You are not coding the solution / function, you’re just testing it! However, you can adapt your function from 0x01. C - Variables, if, else, while - Task #0 to compile with this main file to test locally.



You only need to upload 0-main.c and main.h for this task. We will provide our own positive_or_negative() function.

You are not allowed to add or remove lines of code, you may change only one line in this task.

carrie@ubuntu:/debugging$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 positive_or_negative.c 0-main.c -o 0-main

carrie@ubuntu:/debugging$ ./0-main

0 is zero

carrie@ubuntu:/debugging$ wc -l 0-main.c

16 1-main.c

carrie@ubuntu:/debugging$

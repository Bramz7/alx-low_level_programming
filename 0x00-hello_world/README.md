julien@ubuntu:~/c/0x00$ cat main.c 

#include <stdio.h>



/**

 * main - Entry point

 *

 * Return: Always 0 (Success)

 */

int main(void)

{

    return (0);

}

julien@ubuntu:~/c/0x00$ export CFILE=main.c

julien@ubuntu:~/c/0x00$ ./0-preprocessor 

julien@ubuntu:~/c/0x00$ tail c

# 942 "/usr/include/stdio.h" 3 4



# 2 "main.c" 2





# 3 "main.c"

int main(void)

{

 return (0);

}

julien@ubuntu:~/c/0x00$ 

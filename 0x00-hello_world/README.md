julien@ubuntu:~/c/0x00$ gcc 6-size.c -m32 -o size32 2> /tmp/32

julien@ubuntu:~/c/0x00$ gcc 6-size.c -m64 -o size64 2> /tmp/64

julien@ubuntu:~/c/0x00$ ./size32

Size of a char: 1 byte(s)

Size of an int: 4 byte(s)

Size of a long int: 4 byte(s)

Size of a long long int: 8 byte(s)

Size of a float: 4 byte(s)

julien@ubuntu:~/c/0x00$ ./size64

Size of a char: 1 byte(s)

Size of an int: 4 byte(s)

Size of a long int: 8 byte(s)

Size of a long long int: 8 byte(s)

Size of a float: 4 byte(s)

julien@ubuntu:~/c/0x00$ echo $?

0

julien@ubuntu:~/c/0x00$ 

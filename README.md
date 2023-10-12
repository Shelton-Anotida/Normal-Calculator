This is a Normal Calculator that is able to do:

+: addition
-: subtraction
*: multiplication
/: division
%: modulo

It is created in four different files

This is the command to compile the code

gcc -Wall -pedantic -Werror -Wextra -std=gnu89 3-func.c 3-functions.c 3-get__func.c -o calculate

After compilation examples

./calculate 1 + 1
2

./calculate 97 + 1
98

./calculate 1024 / 10
102

./calculate 1024 '*' 98
100352

./calculate 1024 '\*' 98
Error

./calculate 1024 - 98
926

./calculate 1024 '%' 98
44



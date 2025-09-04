# CISC230 - IAN McDOWELL

## factorial2.cpp

- input/parameter impacting number of calls
    - The number whose factorial is being calculated
- 3 specific examples of input/parameter and number of calls
    - With an input of 4, the function is called 5 times
    - With an input of 7, the function is called 8 times
    - With an input of 9, the function is called 10 times
- number of recursive calls when input/parameter is *n*
    - n + 1

## ireverse2.cpp

- input/parameter impacting number of calls
    - number of digits in the int that is being reversed
- 3 specific examples of input/parameter and number of calls
    - with an input of 1234 (4 digits), the function is called 4 times
    - with an input of 210108 (6 digits), the function is called 6 times
    - with an input of 98437658 (8 digits), the function is called 8 times
- number of recursive calls when input/parameter is *n*
    - n

## sreverse2.cpp

- input/parameter impacting number of calls
    - number of characters in string that is being reversed
- 3 specific examples of input/parameter and number of calls
    - with a string 5 characters long (i.e. "hello"), the function is called 5 times
    - with a string 8 characters long (i.e. "McDowell"), the function is called 8 times
    - with a string 11 characters long (i.e. "hello world"), the function is called 11 times
- number of recursive calls when input/parameter is *n*
    - n

## permute.cpp

- input/parameter impacting number of calls
    - length of string whose permutations are being calculated
- 3 specific examples of input/parameter and number of calls
    - with a string 3 characters long (i.e. "abc"), the function is called 16 times
    - with a string 6 characters long (i.e. "abcdef"), the function is called 1957 times
    - with a string 8 characters long (i.e. "abcdefgh"), the function is called 109601 times
- number of recursive calls when input/parameter is *n*
    - ~3n!

## tower.cpp

- input/parameter impacting number of calls
    - number of disks
- 3 specific examples of input/parameter and number of calls
    - with 3 disks, the function is called 15 times
    - with 7 disks, the function is called 255 times
    - with 9 disks, the function is called 1023 times
- number of recursive calls when input/parameter is *n*
    - 2^(n+1) - 1

## fibonacci2.cpp (presented in video lesson)

- input/parameter impacting number of calls
    - number of fibonacci numbers calculated
- 3 specific examples of input/parameter and number of calls
    - with 20 fibonacci numbers, the function is called 56 times
    - with 50 fibonacci numbers, the function is called 46 times
    - with 7503 fibonacci numbers, the function is called 22505 times
- number of recursive calls when input/parameter is *n*
    - 3n-4

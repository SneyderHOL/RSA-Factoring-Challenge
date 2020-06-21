# Project RSA Factoring Challenge

Optional Project about RSA challenge


factors - is a program that factorize as many numbers as possible into a product of two smallers numbers.

Usage: factors &ltfile&gt

    where <file> is a file containing natural numbers to factor.
    One number per line
    You can assume that all lines will be valid natural numbers greater than 1
    You can assume that there will be no empy line, and no space before and after the valid number
    The file will always end with a new line

Output format: n=p*q

    one factorization per line
    p and q don’t have to be prime numbers
    See example

You can work on the numbers of the file in the order of your choice
Your program should run without any dependency: You will not be able to install anything on the machine we will run your program on


rsa - is a program that factorize a number into a product of two prime numbers.

RSA Laboratories states that: for each RSA number n, there exist prime numbers p and q such that

n = p × q. The problem is to find these two primes, given only n.

This task is the same as factors task, except:

    p and q are always prime numbers
    There is only one number in the files

Usage: rsa &ltfile&gt

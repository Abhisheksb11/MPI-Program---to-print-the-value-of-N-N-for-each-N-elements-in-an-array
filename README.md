# MPI-Program-to-print-the-value-of-N-2-for-each-N-2-elements-and-N-3-for-next-N-2-elements-in-a-array
a program to read a value M and N x M number of elements in the root. Using N processes do the following task. The square of first M numbers, The cube of next M numbers and so on. Printing the results in the root.


mpicc code.c -lm
miexec -n 2 ./a.out code.c

Enter the value for M:- 5
Enter 10 elements:-
1 2 3 4 5 6 7 8 9 10

The 2 power of 1 = 1
The 2 power of 2 = 4
The 2 power of 3 = 9
The 2 power of 4 = 16 
The 2 power of 5 = 25
The 3 power of 6 = 216
The 3 power of 7 = 343
The 3 power of 8 = 512
The 3 power of 9 = 729
The 3 power of 10 = 1000


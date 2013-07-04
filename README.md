N-Queens-Problem
================

This problem is the extension of 8 queens problem, now we have N queens and N x N Chess board. 
This repository contains solution to the N queens problem.

<b>Read Comments on top of .cpp file before running the program</b>

Input:
======
Enter the number of queens for which you want to run the program for: [Enter Integer b/w 1 & 15 here], 
because after 16, the performance of program deteoriates.

Algorithm:
=========
Check file: Algorithm.txt, or check link: http://en.wikipedia.org/wiki/Eight_queens_puzzle  ,or read this
The program finds solutions by starting with a queen in the top left corner of the chess board. 
It then places a queen in the second column and moves it until it finds a place where it cannot be hit 
by the queen in the first column. It then places a queen in the third column and moves it until it cannot b
e hit by either of the first two queens. Then it continues this process with the remaining columns. 
If there is no place for a queen in the current column the program goes back to the preceding column and 
moves the queen in that column. If the queen there is at the end of the column it removes that queen as well 
and goes to the preceding column. If the current column is the last column and a safe place has been found 
for the last queen, then a solution of the puzzle has been found. If the current column is the first column 
and its queen is being moved off the board then all possible configurations have been examined, all solutions
have been found, and the algorithm terminates.

Source: Wikipedia (Just this Text to present on Github)


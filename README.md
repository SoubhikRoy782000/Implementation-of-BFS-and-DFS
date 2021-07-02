# Implementation-of-BFS-and-DFS

Aim -

Given two integers ‘n’ and ‘m’, find all the stepping numbers in range [n, m] by BFS and DFS  approach. (A number is called stepping number if all adjacent digits have an absolute  difference of 1).

Algorithm -

BFS (Breadth First Search) –

STEP 1 – Give the input range n and m. 

STEP 2 – For every single digit Number 'i', find all the Stepping Numbers starting with i.

STEP 3 – Queue will contain all the stepping Numbers

STEP 4 – Get the front element and pop from the queue.

STEP 5 – If the Stepping Number is in the range [n, m] then display.

STEP 6 – If Stepping Number is 0 or greater than m, no need to explore the neighbors.

STEP 7 – Get the last digit of the currently visited Stepping Number

STEP 8 – There can be 2 cases either digit to be appended is lastDigit + 1 or lastDigit - 1

STEP 9 – If lastDigit is 0 then only possible digit after 0 can be 1 for a Stepping Number.

STEP 10 – If lastDigit is 9 then only possible digit after 9 can be 8 for a Stepping Number.

STEP 11 – Printing all stepping numbers in range [n, m] using BFS.25

DFS (Depth First Search) –

STEP 1 – Give the input range n and m. 

STEP 2 – For every single digit Number 'i', find all the Stepping Numbers starting with i.

STEP 3 – If Stepping Number is in the range [n,m] then display.

STEP 4 – If Stepping Number is 0 or greater than m, then return.

STEP 5 – Get the last digit of the currently visited Stepping Number.

STEP 6 – There can be 2 cases either digit to be appended is lastDigit + 1 or lastDigit – 1.

STEP 7 – If lastDigit is 0 then only possible digit after 0 can be 1 for a Stepping Number.

STEP 8 – If lastDigit is 9 then only possible digit after 9 can be 8 for a Stepping Number.

STEP 9 – Printing all stepping numbers in range [n, m] using DFS.

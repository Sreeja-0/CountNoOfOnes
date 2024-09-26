This program counts the number of ones in a binary format of a given number. Below is the example of how program works.

For n = 13 (binary 1101):

First iteration: n = 1101 → n & 1 = 1 → count = 1
Right shift: n = 110 (which is 6)
Second iteration: n = 110 → n & 1 = 0 → count = 1
Right shift: n = 11 (which is 3)
Third iteration: n = 11 → n & 1 = 1 → count = 2
Right shift: n = 1
Fourth iteration: n = 1 → n & 1 = 1 → count = 3
Right shift: n = 0
Final count of ones is 3.

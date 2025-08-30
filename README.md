# Rectangle-3

Question Explanation:

The program is designed to print a rectangle of M rows and N columns, where each row contains the same number that increments with each row. The numbers start from 1 and increase by 1 for each subsequent row.

Logical Approach:

Read Input:
Read two integers, M for the number of rows and N for the number of columns.

Print the Rectangle:
Initialize a counter count to 1.

Use a while loop that runs until count is less than or equal to M (the number of rows).

Inside the loop, print the count number N times (the number of columns), separated by spaces.

After printing each row, increment count by 1.

Output:
This will result in a rectangle where each row contains N columns of the same number, starting from 1 in the first row and increasing by 1 in each subsequent row.

Example for Clarity:

If M = 5 and N = 4, the output will be: 1 1 1 1 2 2 2 2 3 3 3 3 4 4 4 4 5 5 5 5

The first row will contain the number 1 printed N (4) times, the second row will contain the number 2 printed N times, and so on, until the Mth (5th) row.

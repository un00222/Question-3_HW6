**Part 3: Analysis (10 points)**

In a file readme.md analyze your results. Generate 5 runs of the height experiment and put your results into this file. We know from class that the best case height is log2(n) and worst case is n. You are going to try to make a tighter estimate.
Come up with a formula that describes the heights you got in the random experiments. Try to get a reasonably tight range. You do not have to be perfect.
Something like:
2/3 n < average height < n
log2(n) < average height < log2(n)+5
7log2(n) < average height < 9log2(n)
etc...


**Height Experiments Results**

|   N  | Run 1 Avg | Run 2 Avg | Run 3 Avg | Run 4 Avg | Run 5 Avg | 
|------|-----------|-----------|-----------|-----------|-----------|
|     2|       1.00|       1.00|       1.00|       1.00|       1.00| 
|     4|       2.20|       2.20|       2.60|       2.40|       2.00| 
|     8|       4.00|       3.20|       3.80|       3.80|       4.60|
|    16|       6.40|       6.20|       6.20|       5.00|       5.40|
|    32|       8.00|       8.60|       7.60|       8.80|       8.20|
|    64|      10.20|       9.80|      10.00|      10.00|      10.80|
|   128|      15.20|      12.20|      13.40|      13.00|      11.80|
|   256|      16.60|      16.40|      14.60|      16.80|      15.40|
|   512|      19.40|      18.60|      18.40|      18.60|      17.00|
|  1024|      21.20|      21.40|      20.00|      21.00|      21.40|



From these additional runs, we can observe that the average height of the randomly generated binary search trees tends to follow a pattern that is between the best case of log2(n) and the worst case of n.

Based on the data, a reasonable estimation for the average height of a randomly generated binary search tree with n elements could be:
log2(n) < average height < 2*log2(n) + 6

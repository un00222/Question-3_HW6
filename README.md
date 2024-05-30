**Part 3: Analysis (10 points)**
In a file readme.md analyze your results. Generate 5 runs of the height experiment and put your results into this file. We know from class that the best case height is log2(n) and worst case is n. You are going to try to make a tighter estimate.
Come up with a formula that describes the heights you got in the random experiments. Try to get a reasonably tight range. You do not have to be perfect.
Something like:
2/3 n < average height < n
log2(n) < average height < log2(n)+5
7log2(n) < average height < 9log2(n)
etc...

**Ex1:**
Select Option:
1.) Enter Tree Values and print tree.
2.) Run Height Experiments.
2
Experiments (N=Number Element, Table Shows Height)
|   N  |   T1  |   T2  |   T3  |   T4  |   T5  |  Average |
|     2|      1|      1|      1|      1|      1|     1.00|
|     4|      2|      2|      3|      2|      2|     2.20|
|     8|      6|      3|      5|      3|      3|     4.00|
|    16|      5|      6|      6|      8|      7|     6.40|
|    32|      7|      8|      9|      9|      7|     8.00|
|    64|     11|     11|     10|     10|      9|    10.20|
|   128|     15|     21|     15|     12|     13|    15.20|
|   256|     14|     14|     20|     21|     14|    16.60|
|   512|     18|     20|     23|     18|     18|    19.40|
|  1024|     22|     22|     22|     21|     19|    21.20|

**Ex2:**
Select Option:
1.) Enter Tree Values and print tree.
2.) Run Height Experiments.
2
Experiments (N=Number Element, Table Shows Height)
|   N  |   T1  |   T2  |   T3  |   T4  |   T5  |  Average |
|     2|      1|      1|      1|      1|      1|     1.00|
|     4|      3|      2|      2|      2|      2|     2.20|
|     8|      3|      3|      3|      3|      4|     3.20|
|    16|      6|      6|      8|      6|      5|     6.20|
|    32|      9|      8|     10|      6|     10|     8.60|
|    64|     11|     10|     10|      9|      9|     9.80|
|   128|     11|     13|     13|     14|     10|    12.20|
|   256|     14|     16|     16|     16|     20|    16.40|
|   512|     20|     18|     19|     18|     18|    18.60|
|  1024|     22|     24|     21|     20|     20|    21.40|

**Ex3:**
Select Option:
1.) Enter Tree Values and print tree.
2.) Run Height Experiments.
2
Experiments (N=Number Element, Table Shows Height)
|   N  |   T1  |   T2  |   T3  |   T4  |   T5  |  Average |
|     2|      1|      1|      1|      1|      1|     1.00|
|     4|      3|      2|      2|      3|      3|     2.60|
|     8|      4|      5|      3|      4|      3|     3.80|
|    16|      7|      5|      7|      5|      7|     6.20|
|    32|      8|      8|      7|      6|      9|     7.60|
|    64|      8|     10|     10|     12|     10|    10.00|
|   128|     17|     16|     10|     12|     12|    13.40|
|   256|     16|     12|     14|     16|     15|    14.60|
|   512|     19|     17|     19|     17|     20|    18.40|
|  1024|     22|     20|     18|     20|     20|    20.00|

**Ex4:**
Select Option:
1.) Enter Tree Values and print tree.
2.) Run Height Experiments.
2
Experiments (N=Number Element, Table Shows Height)
|   N  |   T1  |   T2  |   T3  |   T4  |   T5  |  Average |
|     2|      1|      1|      1|      1|      1|     1.00|
|     4|      2|      3|      2|      3|      2|     2.40|
|     8|      5|      3|      4|      4|      3|     3.80|
|    16|      5|      5|      4|      5|      6|     5.00|
|    32|      7|     11|      9|      9|      8|     8.80|
|    64|      9|     10|     11|      9|     11|    10.00|
|   128|     12|     14|     13|     11|     15|    13.00|
|   256|     19|     17|     16|     17|     15|    16.80|
|   512|     21|     21|     17|     18|     16|    18.60|
|  1024|     22|     20|     19|     24|     20|    21.00|

**Ex5:**
Select Option:
1.) Enter Tree Values and print tree.
2.) Run Height Experiments.
2
Experiments (N=Number Element, Table Shows Height)
|   N  |   T1  |   T2  |   T3  |   T4  |   T5  |  Average |
|     2|      1|      1|      1|      1|      1|     1.00|
|     4|      2|      2|      2|      2|      2|     2.00|
|     8|      5|      5|      3|      4|      6|     4.60|
|    16|      4|      6|      6|      5|      6|     5.40|
|    32|      7|     11|      6|      9|      8|     8.20|
|    64|     12|     12|      9|     10|     11|    10.80|
|   128|     12|     14|     11|     11|     11|    11.80|
|   256|     16|     15|     13|     18|     15|    15.40|
|   512|     18|     15|     16|     18|     18|    17.00|
|  1024|     21|     20|     24|     19|     23|    21.40|

From these additional runs, we can observe that the average height of the randomly generated binary search trees tends to follow a pattern that is between the best case of log2(n) and the worst case of n.

Based on the data, a reasonable estimation for the average height of a randomly generated binary search tree with n elements could be:
log2(n) < average height < 2*log2(n) + 6

The 20 0-1 knapsack problem is generated used the follow program:
http://www.diku.dk/~pisinger/generator.c

The parameter settings of the program is:
type
 1 = uc = uncorr. 
 2 = wc = weakly corr. 
 3 = sc = strongly corr. 
 4 = ss = subset sum 

n = 100,200,300,500,1000
r = 100
i = 100
S = 1000

The format of these data files is as the follow example:

10       // N number of objects
1  2  1  // 1 p(1) w(1)
2  2  2  // 2 p(2) w(2)
3  4  4  // 3 ...
4  4  1
5  1  2
6  1  3
7  1  3
8  3  1
9  2  3
10 2  4
5        // Knapsack capacity C
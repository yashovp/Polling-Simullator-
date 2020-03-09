# Polling-Simullator-

The program takes the following type of polling data where each row is the order of preference of a voter, where first 
postion implies first preferance.

For example, consider an election with five candidates whom we will 
call A, B, C, D and E. One voter might rank the candidates this way:
DABCE


Example of data input:

D E C B A
A B C D E
D E C B A
A B C D E
E D C B A

After accepting the input data, the program runs five different methods of polling, all algorithms of which run in O(n) time, 
to conduct different type of polling analysis on the data. 


A PLurality winner is the candidate with the most amount of first preferance votes.

A Majority winner is the candidate who was able to achieve more than 50% of the first 
preferance votes.

A broda winner is decided by assigning a weight to the preferance ranking votes, adding 
them all up and then declaring a winner, which is the candidate with the most amount of points.

A Approval winner is decided where voters may vote for candidates that they approve off, here,
ranking does not matter. The candidate with the most votes wins.

A condorcet winner is a candidate who would win a two candidate election against all 
the other candidates in a plurality votes.





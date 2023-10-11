# ActivityVRP
Vehicle routing problem with gurobipy

Operations Research II (Continues Assignment – 01)
A logistics company located at the Node 01 has to distribute goods other nodes (Node 02, Node 03, …., 
Node 31). Location of nodes are given in (x, y) coordinates in the following table. Capacity of a truck 
is 90 MT. 
You are required to find the following:
a) Declare decision variables, parameters and indices. (10 marks)
b) Construct the distance matrix. (10 marks)
c) Formulate the Mixed-Integer Linear Programming model. (30 marks)
d) Find solutions using MS Excel Solver or any solver available in python. (40 marks) 
e) Discuss the assumptions that you made and the implications of the answer(s) you found in the 
above. (10 marks)
[100 marks]
Node X - coordinate Y - coordinate Demand, MT
1 50 50
2 92 2.43 17
3 4.43 86.1 4
4 70.6 29.6 5
5 36.3 35 10
6 20.3 93.3 2
7 65 94.5 13
8 80.5 75.1 19
9 44.3 8.05 17
10 55.4 46.9 5
11 90.8 52.4 12
12 90.2 87.3 7
13 30.9 69.9 14
14 89.5 72.8 7
15 81.7 32.1 9
16 17 83.3 10
17 87.3 57.6 17
18 83.7 8.73 20
19 96.9 45.5 18
20 59.6 16.5 14
21 71.8 45.5 8
22 92.3 29.1 20
23 73.1 63.6 12
24 21.4 9.61 8
25 11.8 34.8 19
26 6.89 42.6 17
27 43.3 52 8
28 86 86.8 13
29 26.9 91.6 17
30 29.1 55.6 6
31 7.4 24 16

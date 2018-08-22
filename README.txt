---------------------------------
Input/Output 
---------------------------------

1. The Input for initial state and goal state should be given line by line. Only one space and numbers from 1 to 8 should be given for initial and goal state.

2. All expanded states are given as output. Along with states parent node number, current node number, F(n), heuristic function value and path cost is displayed. Once goal state is reached Nodes generated and nodes expanded list is displayed.

---------------------------------
Sample input and output
---------------------------------
Enter Start node
1
2
3
7
5
6
8
4
 
Enter Goal node
1
2
3
4
5
6
7
8
 
Start of searching node

Expanding node

1	2	3	
7	5	6	
8	4	 	

F(n)=4.0
Path Cost till now 0.0
h(n) value:4.0
Parent Node number:0
Current node number1

Expanding node

1	2	3	
7	5	 	
8	4	6	

F(n)=6.0
Path Cost till now 1.0
h(n) value:5.0
Parent Node number:1
Current node number3

Expanding node

1	2	3	
7	5	6	
8	 	4	

F(n)=6.0
Path Cost till now 1.0
h(n) value:5.0
Parent Node number:1
Current node number2

Expanding node

1	2	3	
7	5	6	
 	8	4	

F(n)=6.0
Path Cost till now 2.0
h(n) value:4.0
Parent Node number:2
Current node number6

Expanding node

1	2	3	
 	5	6	
7	8	4	

F(n)=6.0
Path Cost till now 3.0
h(n) value:3.0
Parent Node number:6
Current node number8

Expanding node

 	2	3	
1	5	6	
7	8	4	

F(n)=8.0
Path Cost till now 4.0
h(n) value:4.0
Parent Node number:8
Current node number10

Expanding node

1	2	3	
5	 	6	
7	8	4	

F(n)=8.0
Path Cost till now 4.0
h(n) value:4.0
Parent Node number:8
Current node number9

Expanding node

1	2	3	
7	 	6	
8	5	4	

F(n)=8.0
Path Cost till now 2.0
h(n) value:6.0
Parent Node number:2
Current node number7

Expanding node

1	2	3	
7	 	5	
8	4	6	

F(n)=8.0
Path Cost till now 2.0
h(n) value:6.0
Parent Node number:3
Current node number4

Expanding node

1	2	3	
7	4	5	
8	 	6	

F(n)=8.0
Path Cost till now 3.0
h(n) value:5.0
Parent Node number:4
Current node number20

Expanding node

1	2	3	
7	4	5	
 	8	6	

F(n)=8.0
Path Cost till now 4.0
h(n) value:4.0
Parent Node number:20
Current node number21

Expanding node

1	2	3	
 	4	5	
7	8	6	

F(n)=8.0
Path Cost till now 5.0
h(n) value:3.0
Parent Node number:21
Current node number23

Expanding node

1	2	3	
4	 	5	
7	8	6	

F(n)=8.0
Path Cost till now 6.0
h(n) value:2.0
Parent Node number:23
Current node number24

Expanding node

1	2	3	
4	5	 	
7	8	6	

F(n)=8.0
Path Cost till now 7.0
h(n) value:1.0
Parent Node number:24
Current node number26

Expanding node

1	2	3	
4	5	6	
7	8	 	

F(n)=8.0
Path Cost till now 8.0
h(n) value:0.0
Parent Node number:26
Current node number30
Time:7
Goal state reached

1	2	3	
4	5	6	
7	8	 	
Nodes Generated:30
Number of nodes expanded:14


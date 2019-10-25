# COMP110 Worksheet 4

Please edit this README.md file with your answers to the worksheet questions.

## Question 1

### a
A and B and not C
A	|	B	|	C	|	Output
False	|	False	|	False	|	False	
False	|	False	|	True	|	False	
False	|	True	|	False	|	False	
False	|	True	|	True	|	False	
True	|	False	|	False	|	False	
True	|	False	|	True	|	False	
True	|	True	|	False	|	True	
True	|	True	|	True	|	False	

### b
A and not (B and not C)
A	|	B	|	C	|	Output
False	|	False	|	False	|	False
False	|	False	|	True	|	False
False	|	True	|	False	|	False
False	|	True	|	True	|	False
True	|	False	|	False	|	True
True	|	False	|	True	|	True
True	|	True	|	False	|	False
True	|	True	|	True	|	True

### c
(A or not B) and (A or C)
A	|	B	|	C	|	Out
False	|	False	|	False	|	False
False	|	False	|	True	|	True
False	|	True	|	False	|	False
False	|	True	|	True	|	False
True	|	False	|	False	|	True
True	|	False	|	True	|	True
True	|	True	|	False	|	True
True	|	True	|	True	|	True

### d
A and not (B or not C) and (not A and D)
A	|	B	|	C	|	D	|	Out
False	|	False	|	False	|	False	|	False
False	|	False	|	False	|	True	|	False
False	|	False	|	True	|	False	|	False
False	|	False	|	True	|	True	|	False
False	|	True	|	False	|	False	|	False
False	|	True	|	False	|	True	|	False
False	|	True	|	True	|	False	|	False
False	|	True	|	True	|	True	|	False
True	|	False	|	False	|	False	|	False
True	|	False	|	False	|	True	|	False
True	|	False	|	True	|	False	|	False
True	|	False	|	True	|	True	|	False
True	|	True	|	False	|	False	|	False
True	|	True	|	False	|	True	|	False
True	|	True	|	True	|	False	|	False
True	|	True	|	True	|	True	|	False

## Question 2

### a
![Chart for 2a](1A.png)

### b
![Chart for 2b](1B.png)

### c
![Chart for 2c](1C.png)

### d
![Chart for 2d](1D.png	)

## Question 3

### a
not (A or B) == 	not A and not B
0 0 ->	1	|	0 0 ->	1
0 1 ->	0	|	0 1 -> 	0
1 0 ->	0	|	1 0 -> 	0
1 1 ->	0	|	1 1 -> 	0

### b
not (A and B) == not A or not B
0 0 -> !(0.0) ->	1	|	0 0 -> !0+!0 ->	1
0 1 -> !(0.1) ->	1	|	0 1 -> !0+!1 ->	1
1 0 -> !(1.0) ->	1	|	1 0 -> !1+!0 ->	1
1 1 -> !(1.1) ->	0	|	1 1 -> !1+!1 ->	0

### c
(A and B) or (A and C) == A and (B or C) 
0 0 0 -> (0.0)+(0.0) ->	0	|	0 0 0 -> 0.(0+0) ->	0
0 0 1 -> (0.0)+(0.1) ->	0	|	0 0 1 -> 0.(0+1) ->	0
0 1 0 -> (0.1)+(0.0) ->	0	|	0 1 0 -> 0.(1+0) ->	0
0 1 1 -> (0.1)+(0.1) ->	0	|	0 1 1 -> 0.(1+1) ->	0
1 0 0 -> (1.0)+(1.0) ->	0	|	1 0 0 -> 1.(0+0) ->	0
1 0 1 -> (1.0)+(1.1) ->	1	|	1 0 1 -> 1.(0+1) ->	1
1 1 0 -> (1.1)+(1.0) ->	1	|	1 1 0 -> 1.(1+0) ->	1
1 1 1 -> (1.1)+(1.1) ->	1	|	1 1 1 -> 1.(1+1) ->	1

### d
(A or B) and (A or C) == A or (B and C)
0 0 0 -> (0+0).(0+0) ->	0	|	0 0 0 -> 0+(0.0) ->	0
0 0 1 -> (0+0).(0+1) ->	0	|	0 0 1 -> 0+(0.1) ->	0
0 1 0 -> (0+1).(0+0) ->	0	|	0 1 0 -> 0+(1.0) ->	0
0 1 1 -> (0+1).(0+1) ->	1	|	0 1 1 -> 0+(1.1) ->	1
1 0 0 -> (1+0).(1+0) ->	1	|	1 0 0 -> 1+(0.0) ->	1
1 0 1 -> (1+0).(1+1) ->	1	|	1 0 1 -> 1+(0.1) ->	1
1 1 0 -> (1+1).(1+0) ->	1	|	1 1 0 -> 1+(1.0) ->	1
1 1 1 -> (1+1).(1+1) ->	1	|	1 1 1 -> 1+(1.1) ->	1

## Question 4

### a
if not(file_exists("a.txt") and file_exists("b.txt")): print("A required file is missing")
if not file_exists("a.txt") or not file_exists("b.txt"): print("A required file is missing")
To prove these are equivalent to an equasion, I will simplify them to just the bool checks.
The first simplifies to not(A and B) and the second simplifies to (not A or not B).
This means it is equivalent to 3.B

### b
if (type(x) == int and x > 7) or (type(x) == float and x > 7): print("Hello")
if (type(x) == int or type(x) == float) and x > 7: print("Hello")
Simplified the first: (A and B) or (C and B)
This is equivalent to (A and B) or (A and C)
For the second: (A or B) and C
This is equivalent of A and (B or C)
These will have the same truth table as 3.C

### c
if x == 0 and y == 0: do_something() else: print("Do nothing")
if x != 0 or y != 0: print("Do nothing") else: do_something()
Simplified the first: not A and not B
Simplified the second: not(A or B)
The reason this works is because when you are checking if something is equal to 0 in a programming language, you are generally checking if it is false. If you are not equal to zero the item is true because it contains data.
This expression (simplified) is the same as 3.A

### d
if x > 10 or (x > 0 and y > 0): do_something()
if x > 0 and (x > 10 or y > 0): do_something()
Simplified the first: A or (B and C)
Simplified the second: B and (A or C)
When you and a boolean to a set of brackets, you expand it like this: (B and A) or (B and C)
Knowing this, it is equivalant to 3.D
# COMP110 Worksheet 4

Please edit this README.md file with your answers to the worksheet questions.

## Question 1

### a
A | B | C | A AND B AND NOT C
-------------|-------------|-------------|-------------
False	|	False	|	False	|	False
False	|	False	|	True	|	False
False	|	True	|	False	|	False
False	|	True	|	True	|	False
True	|	False	|	False	|	False
True	|	False	|	True	|	False
True	|	True	|	False	|	True
True	|	True	|	True	|	False

### b
A| B | C | A AND NOT (B AND NOT C)|
-------------|-------------|-------------|-------------
False	|	False	|	False	|	False
False	|	False	|	True	|	False
False	|	True	|	False	|	False
False	|	True	|	True	|	False
True	|	False	|	False	|	True
True	|	False	|	True	|	True
True	|	True	|	False	|	False
True	|	True	|	True	|	True

### c
A | B | C | (A OR NOT B) AND (A OR C)
-------------|-------------|-------------|-------------
False	|	False	|	False	|	False
False	|	False	|	True	|	True
False	|	True	|	False	|	False
False	|	True	|	True	|	False
True	|	False	|	False	|	True
True	|	False	|	True	|	True
True	|	True	|	False	|	True
True	|	True	|	True	|	True

### d
A | B | C| D |A AND NOT (B OR NOT C) AND (NOT A AND D)
-------------|-------------|-------------|-------------|-------------
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

![Question_2_Answers](https://i.imgur.com/YvaYtgY.png)

## Question 3

### a
A | B | NOT (A OR B)
-------------|-------------|-------------
False	|	False	|	True
False	|	True	|	False
True	|	False	|	False
True	|	True	|	False
	IS the same as
A | B | NOT A AND NOT B
-------------|-------------|-------------
False	|	False	|	True
False	|	True	|	False
True	|	False	|	False
True	|	True	|	False

### b
A | B | NOT (A AND B)
-------------|-------------|-------------
False	|	False	|	True
False	|	True	|	True
True	|	False	|	True
True	|	True	|	False
	IS the same as
A | B | NOT A OR NOT B
-------------|-------------|-------------
False	|	False	|	True
False	|	True	|	True
True	|	False	|	True
True	|	True	|	False

### c
A | B | C | (A AND B) OR (A AND C)
-------------|-------------|-------------|-------------
False	|	False	|	False	|	False
False	|	False	|	True	|	False
False	|	True	|	False	|	False
False	|	True	|	True	|	False
True	|	False	|	False	|	False
True	|	False	|	True	|	True
True	|	True	|	False	|	True
True	|	True	|	True	|	True
	IS the same as
A | B | C | A AND (B OR C)
-------------|-------------|-------------|-------------
False	|	False	|	False	|	False
False	|	False	|	True	|	False
False	|	True	|	False	|	False
False	|	True	|	True	|	False
True	|	False	|	False	|	False
True	|	False	|	True	|	True
True	|	True	|	False	|	True
True	|	True	|	True	|	True

### d
A | B | C | (A OR B) AND (A OR C)
-------------|-------------|-------------|-------------
False	|	False	|	False	|	False
False	|	False	|	True	|	False
False	|	True	|	False	|	False
False	|	True	|	True	|	True
True	|	False	|	False	|	True
True	|	False	|	True	|	True
True	|	True	|	False	|	True
True	|	True	|	True	|	True
	IS the same as
A | B | C | A OR (B AND C)
-------------|-------------|-------------|-------------
False	|	False	|	False	|	False
False	|	False	|	True	|	False
False	|	True	|	False	|	False
False	|	True	|	True	|	True
True	|	False	|	False	|	True
True	|	False	|	True	|	True
True	|	True	|	False	|	True
True	|	True	|	True	|	True

## Question 4

### a
If "a.txt" or "b.txt" are missing, then print "A required file is missing".

### b
If x is of type int or float and x is greater than 7, print "Hello".

### c
If x = y to 0 then, run method do_something().

### d
If x is < 10 or x and y are greater than 0 then, run method do_something().

# COMP110 Worksheet 4

Please edit this README.md file with your answers to the worksheet questions.

## Question 1

### a

| A | B	| C	| A AND B	|	A AND B AND NOT C |
|---|---|---|---|---|
| TRUE	| TRUE | TRUE	| TRUE	| FALSE |
| TRUE	| TRUE | FALSE | TRUE	| TRUE |
| TRUE	| FALSE	| TRUE	| FALSE	| FALSE |
| TRUE	| FALSE	| FALSE	| FALSE	| FALSE |
| FALSE	| TRUE	| TRUE	| FALSE	| FALSE |
| FALSE	| TRUE	| FALSE	| FALSE	| FALSE |
| FALSE	| FALSE	| TRUE	| FALSE	| FALSE |
| FALSE	| FALSE	| FALSE	| FALSE	| FALSE |

### b

| A	| B	| C	| B AND NOT C	| A AND NOT (B AND NOT C) |
|---|---|---|---|---|
| TRUE	| TRUE	| TRUE	| FALSE		| TRUE |
| TRUE	| TRUE	| FALSE	| TRUE		| FALSE |
| TRUE	| FALSE	| TRUE	| FALSE		| TRUE |
| TRUE	| FALSE	| FALSE	| FALSE		| TRUE |
| FALSE	| TRUE	| TRUE	| FALSE		| FALSE |
| FALSE	| TRUE	| FALSE	| TRUE		| FALSE |
| FALSE	| FALSE	| TRUE	| FALSE		| FALSE |
| FALSE	| FALSE	| FALSE	| FALSE		| FALSE |

### c

| A	| B	| C	| A OR NOT B	| A OR C		| (A OR NOT B) AND (A OR C) |
|---|---|---|---|---|---|
| TRUE	| TRUE	| TRUE	| TRUE		| TRUE		| TRUE |
| TRUE	| TRUE	| FALSE	| TRUE		| TRUE		| TRUE |
| TRUE	| FALSE	| TRUE	| TRUE		| TRUE		| TRUE |
| TRUE	| FALSE	| FALSE	| TRUE		| TRUE		| TRUE |
| FALSE	| TRUE	| TRUE	| FALSE		| TRUE		| FALSE |
| FALSE	| TRUE	| FALSE	| FALSE		| FALSE		| FALSE |
| FALSE	| FALSE	| TRUE	| TRUE		| TRUE		| TRUE |
| FALSE	| FALSE	| FALSE	| TRUE		| FALSE		| FALSE |


### d

| A	| B	| C	| D	| B OR NOT C	| NOT A AND D	| A AND NOT (B OR NOT C) AND (NOT A AND D)| 
|---|---|---|---|---|---|---|
| TRUE	| TRUE	| TRUE	| TRUE	| TRUE		| FALSE		| FALSE| 
| TRUE	| TRUE	| TRUE	| FALSE	| TRUE		| TRUE		| FALSE| 
| TRUE	| TRUE	| FALSE	| TRUE	| TRUE		| FALSE		| FALSE| 
| TRUE	| TRUE	| FALSE	| FALSE	| TRUE		| TRUE		| FALSE| 
| TRUE	| FALSE	| TRUE	| TRUE	| FALSE		| FALSE		| FALSE| 
| TRUE	| FALSE	| TRUE	| FALSE	| FALSE		| TRUE		| TRUE| 
| TRUE	| FALSE	| FALSE	| TRUE	| TRUE		| FALSE		| FALSE| 
| TRUE	| FALSE	| FALSE	| FALSE	| TRUE		| TRUE		| FALSE| 
| FALSE	| TRUE	| TRUE	| TRUE	| TRUE		| TRUE		| FALSE| 
| FALSE	| TRUE	| TRUE	| FALSE	| TRUE		| FALSE		| FALSE| 
| FALSE	| TRUE	| FALSE	| TRUE	| TRUE		| TRUE		| FALSE| 
| FALSE	| TRUE	| FALSE	| FALSE	| TRUE		| FALSE		| FALSE| 
| FALSE	| FALSE	| TRUE	| TRUE	| FALSE		| TRUE		| FALSE| 
| FALSE	| FALSE	| TRUE	| FALSE	| FALSE		| FALSE		| FALSE| 
| FALSE	| FALSE	| FALSE	| TRUE	| TRUE		| TRUE		| FALSE| 
| FALSE	| FALSE	| FALSE	| FALSE	| TRUE		| FALSE		| FALSE| 

## Question 2

### a

![](https://github.com/EugeneFalmouth/comp110-worksheet-4/blob/master/Worksheet4_2a.png "Question 2a")

### b

![](https://github.com/EugeneFalmouth/comp110-worksheet-4/blob/master/Worksheet4_2b.png "Question 2b")

### c

![](https://github.com/EugeneFalmouth/comp110-worksheet-4/blob/master/Worksheet4_2c.png "Question 2c")

### d

![](https://github.com/EugeneFalmouth/comp110-worksheet-4/blob/master/Worksheet4_2d.png "Question 2d")

## Question 3

### a

| A	| B	| NOT (A OR B)	| NOT A AND NOT B | 
|---|---|---|---|
| TRUE	| TRUE	| FALSE		| FALSE | 
| TRUE	| FALSE	| FALSE		| FALSE | 
| FALSE	| TRUE	| FALSE		| FALSE | 
| FALSE |	FALSE	| TRUE		| TRUE | 

### b

| A	| B	| NOT (A AND B)	| NOT A OR NOT B | 
|---|---|---|---|
| TRUE	| TRUE	| FALSE		| FALSE | 
| TRUE	| FALSE	| TRUE		| TRUE | 
| FALSE	| TRUE	| TRUE		| TRUE | 
| FALSE	| FALSE	| TRUE		| TRUE | 

### c

| A	| B	| C	| (A AND B) OR (A AND C)	| A AND (B OR C) | 
|---|---|---|---|---|
| TRUE	| TRUE	| TRUE	| TRUE			| TRUE | 
| TRUE	| TRUE	| FALSE	| TRUE			| TRUE |
| TRUE	| FALSE	| TRUE	| TRUE			| TRUE |
| TRUE	| FALSE	| FALSE	| FALSE			| FALSE |
| FALSE	| TRUE	| TRUE	| FALSE			| FALSE |
| FALSE	| TRUE	| FALSE	| FALSE			| FALSE |
| FALSE	| FALSE	| TRUE	| FALSE			| FALSE |
| FALSE	| FALSE	| FALSE	| FALSE			| FALSE |

### d

| A	| B	| C	| (A OR B) AND (A OR C)	| A OR (B AND C) |
|---|---|---|---|---|
| TRUE	| TRUE	| TRUE	| TRUE			| TRUE |
| TRUE	| TRUE	| FALSE	| TRUE			| TRUE |
| TRUE	| FALSE	| TRUE	| TRUE			| TRUE |
| TRUE	| FALSE	| FALSE	| TRUE			| TRUE |
| FALSE	| TRUE	| TRUE	| TRUE			| TRUE |
| FALSE	| TRUE	| FALSE	| FALSE			| FALSE |
| FALSE	| FALSE	| TRUE	| FALSE			| FALSE |
| FALSE	| FALSE	| FALSE	| FALSE			| FALSE |

## Question 4

### a

If we assume that 'file_exists ("a.txt ")' is equal to event A and 'file_exists ("b.txt ")' is equal to event B then both programs can be simplified to identity B in question 3

### b

If we assume that 'x > 7' is equal to event A, 'type (x) == int' is equal to event B and 'type (x) == float' is equal to event C then both programs can be simplified to identity C in question 3

### c

If we assume that 'x == 0' is equal to event A and 'y == 0' is equal to event B then we can make a truth table:

| A	| B	| A AND B		| NOT A OR NOT B | 
|---|---|---|---|
| TRUE	| TRUE	| TRUE		| FALSE | 
| TRUE	| FALSE	| FALSE		| TRUE | 
| FALSE	| TRUE	| FALSE		| TRUE | 
| FALSE	| FALSE	| FALSE		| TRUE | 

Both if statements always have opposite results (TRUE or FALSE) but since the executed code within the if/else statement is swapped, both programs execute the same code with any inputs as long as they are the same for both programs.

### d

If we assume that 'x > 10' is equal to event A, 'x > 0' is equal to event B and 'y > 0' is equal to event C then we can make a truth table:

| A	| B	| C	| A OR (B AND C)		| B AND (A OR C) | 
|---|---|---|---|---|
| TRUE	| TRUE	| FALSE	| TRUE			| TRUE | 
| TRUE	| TRUE	| TRUE	| TRUE			| TRUE | 
| TRUE	| FALSE	| FALSE	| TRUE			| FALSE | 
| TRUE	| FALSE	| TRUE	| TRUE			| FALSE | 
| FALSE	| TRUE	| FALSE	| FALSE			| FALSE | 
| FALSE	| TRUE	| TRUE	| TRUE			| TRUE | 
| FALSE	| FALSE	| FALSE	| FALSE			| FALSE | 
| FALSE	| FALSE	| TRUE	| FALSE			| FALSE | 

The two if statements don't always have the same result, meaning that the two programs are actually not equivalent

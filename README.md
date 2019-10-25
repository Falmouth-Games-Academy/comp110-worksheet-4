# COMP110 Worksheet 4

Please edit this README.md file with your answers to the worksheet questions.

## Question 1

### a

|    A    |    B    |    C    |    A and B and not C    |
|---------|---------|---------|-------------------------|
|    F    |    F    |    F    |    F                    |
|    F    |    F    |    T    |    F                    |
|    F    |    T    |    F    |    F                    |
|    F    |    T    |    T    |    F                    |
|    T    |    F    |    F    |    F                    |
|    T    |    F    |    T    |    F                    |
|    T    |    T    |    F    |    T                    |
|    T    |    T    |    T    |    F                    |

### b

|    A    |    B    |    C    |    A and not (B and not C)    |
|---------|---------|---------|-------------------------------|
|    F    |    F    |    F    |    F                          |
|    F    |    F    |    T    |    F                          |
|    F    |    T    |    F    |    F                          |
|    F    |    T    |    T    |    F                          |
|    T    |    F    |    F    |    T                          |
|    T    |    F    |    T    |    T                          |
|    T    |    T    |    F    |    F                          |
|    T    |    T    |    T    |    T                          |

### c

|    A    |    B    |    C    |    (A or not B) and (A or   C)    |
|---------|---------|---------|-----------------------------------|
|    F    |    F    |    F    |    F                              |
|    F    |    F    |    T    |    T                              |
|    F    |    T    |    F    |    F                              |
|    F    |    T    |    T    |    F                              |
|    T    |    F    |    F    |    T                              |
|    T    |    F    |    T    |    T                              |
|    T    |    T    |    F    |    F                              |
|    T    |    T    |    T    |    F                              |

### d

|    A    |    B    |    C    |    D    |    A and not (B or not C) and (not A and D)    |
|---------|---------|---------|---------|------------------------------------------------|
|    F    |    F    |    F    |    F    |    F                                           |
|    F    |    F    |    F    |    T    |    F                                           |
|    F    |    F    |    T    |    F    |    F                                           |
|    F    |    F    |    T    |    T    |    F                                           |
|    F    |    T    |    F    |    F    |    F                                           |
|    F    |    T    |    F    |    T    |    F                                           |
|    F    |    T    |    T    |    F    |    F                                           |
|    F    |    T    |    T    |    T    |    F                                           |
|    T    |    F    |    F    |    F    |    F                                           |
|    T    |    F    |    F    |    T    |    F                                           |
|    T    |    F    |    T    |    F    |    F                                           |
|    T    |    F    |    T    |    T    |    F                                           |
|    T    |    T    |    F    |    F    |    F                                           |
|    T    |    T    |    F    |    T    |    F                                           |
|    T    |    T    |    T    |    F    |    F                                           |
|    T    |    T    |    T    |    T    |    F                                           |

## Question 2

### a
![2A](https://raw.githubusercontent.com/TrainerIsaac/comp110-worksheet-4/master/2A.jpg)
### b
![2B](https://raw.githubusercontent.com/TrainerIsaac/comp110-worksheet-4/master/2B.jpg)
### c
![2C](https://raw.githubusercontent.com/TrainerIsaac/comp110-worksheet-4/master/2C.jpg)
### d
![2D](https://raw.githubusercontent.com/TrainerIsaac/comp110-worksheet-4/master/2D.jpg)

## Question 3

### a

| A | B | Not (A or B) |
|---|---|--------------|
| F | F | T            |
| F | T | F            |
| T | F | F            |
| T | T | F            |

=

| a | b | not A and not B |
|---|---|-----------------|
| F | F | T               |
| F | T | F               |
| T | F | F               |
| T | T | F               |

### b

| a | b | not (a and b) |
|---|---|---------------|
| F | F | T             |
| F | T | T             |
| T | F | T             |
| T | T | F             |

=

| a | b | a or not b |
|---|---|------------|
| F | F | T          |
| F | T | F          |
| T | F | T          |
| T | T | T          |

### c

| A | B | C | (a and b) or (a and c) |
|---|---|---|------------------------|
| F | F | F | F                      |
| F | F | T | F                      |
| F | T | F | F                      |
| F | T | T | F                      |
| T | F | F | F                      |
| T | F | T | T                      |
| T | T | F | T                      |
| T | T | T | T                      |

=

| A | B | C |     a and (b or c)     |
|---|---|---|------------------------|
| F | F | F | F                      |
| F | F | T | F                      |
| F | T | F | F                      |
| F | T | T | F                      |
| T | F | F | F                      |
| T | F | T | T                      |
| T | T | F | T                      |
| T | T | T | T                      |

### d

| a | b | c |(a or b) and (b or c)|
|---|---|---|---------------------|
| F | F | F | F                   |
| F | F | T | F                   |
| F | T | F | F                   |
| F | T | T | T                   |
| T | F | F | T                   |
| T | F | T | T                   |
| T | T | F | T                   |
| T | T | T | T                   |

=

| a | b | c |  a or (b and c)  |
|---|---|---|------------------|
| F | F | F | F                |
| F | F | T | F                |
| F | T | F | F                |
| F | T | T | T                |
| T | F | F | T                |
| T | F | T | T                |
| T | T | F | T                |
| T | T | T | T                |

## Question 4

### a

The major difference between both pieces of code are the use of 'or' in one context, with 'and' in the other. The code using the 'and' references both '.txt' files together in brackets, meaning the system will check if both 'a.txt' and 'b.txt' exist. If either one doesn't exist, the condition will not be met and 'A required file is missing' will be printed.

This functions the same as the 'or' function, as it uses a 'not' keyword before checking each '.txt' file, essentially checking that, if either the 'a' or 'b' file are not there, the message 'A required file is missing' will display, having the exact same function as the code using 'and'. 

### b

The first script checks if 'tpye(x)' is equal to two values: (int and x > 7) or (float and x > 7). It checks if 'type(x)' is equal to each of these values one after the other, and uses brackets to seperate both equasions. If 'type(x)' is equal to either one of these (checked using the 'or' keyword), it will display the message 'Hello'. As x > 7 is in both sets of brackets, then the message will not display if x > 7 is not true.

The second script checks if 'type(x)' is equal to equal to (int or float) and x > 7. This functionally does the same as the previous script, as it also checks if 'type(x)' is equal to int or float, but rather than checking if x > 7 twice with both int and float, the script simply checks if 'type(x)' is equal to int or float in one set of brackets, and ensures x > 7 seperately from this once at the end. 

### c

Only if X and y simultaniously equal 0, the program will launch the 'do_something' function. If they don't, the program will print 'do nothing'.

If x or y don't equal zero, the program will print 'do nothing', however, if x or y not equalling 0 is false (which means x and y being equal to zero 0) the 'do_something' function will be launched.

### d

The first piece of code checks if x > 10 first, then checks if x > 10 and y > 0, only when x > 10 is false. If only one of these items is true, then the 'do_something' function is called

The second piece of code checks if x > 0 first, then checking whether one of x > 10 or y > 0 is true. If both of these checks return as true, then the 'do_something' function is called.

Each piece of code allows one of x > 10 or x > 0 to be false, in conjunction with the other value being true. y > 0 is always checked, and is compared to both x > 10 and x > 0. Therefore, both pieces of code have the same function.

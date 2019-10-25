# COMP110 Worksheet 4
George Jenkins answers 

## Question 1

### a
|    A        |    B        |    C        |    Not C    |    A and B and Not C    |
|-------------|-------------|-------------|-------------|-------------------------|
|    False    |    False    |    False    |    True     |    False                |
|    False    |    False    |    True     |    False    |    False                |
|    False    |    True     |    False    |    True     |    False                |
|    False    |    True     |    True     |    False    |    False                |
|    True     |    False    |    False    |    True     |    False                |
|    True     |    False    |    True     |    False    |    False                |
|    True     |    True     |    False    |    True     |    True                 |
|    True     |    True     |    True     |    False    |    False                |

### b
|    A        |    B        |    C        |    Not(B and Not C)    |    A and Not(B and Not C)    |
|-------------|-------------|-------------|------------------------|------------------------------|
|    False    |    False    |    False    |    True                |    False                     |
|    False    |    False    |    True     |    True                |    False                     |
|    False    |    True     |    False    |    False               |    False                     |
|    False    |    True     |    True     |    True                |    False                     |
|    True     |    False    |    False    |    True                |    True                      |
|    True     |    False    |    True     |    True                |    True                      |
|    True     |    True     |    False    |    False               |    False                     |
|    True     |    True     |    True     |    True                |    True                      |

### c
|    A        |    B        |    C        |    A or Not B    |    A or C    |    (A OR NOT B) AND (A OR C)    |
|-------------|-------------|-------------|------------------|--------------|---------------------------------|
|    False    |    False    |    False    |    True          |    False     |    False                        |
|    False    |    False    |    True     |    True          |    True      |    True                         |
|    False    |    True     |    False    |    False         |    False     |    False                        |
|    False    |    True     |    True     |    False         |    True      |    False                        |
|    True     |    False    |    False    |    True          |    True      |    True                         |
|    True     |    False    |    True     |    True          |    True      |    True                         |
|    True     |    True     |    False    |    True          |    True      |    True                         |
|    True     |    True     |    True     |    True          |    True      |    True                         |

### d
|    A        |    B        |    C        |    D        |    A AND NOT (B OR NOT C) AND (NOT A AND D)    |
|-------------|-------------|-------------|-------------|------------------------------------------------|
|    False    |    False    |    False    |    False    |    False                                       |
|    False    |    False    |    False    |    True     |    False                                       |
|    False    |    False    |    True     |    False    |    False                                       |
|    False    |    False    |    True     |    True     |    False                                       |
|    False    |    True     |    False    |    False    |    False                                       |
|    False    |    True     |    False    |    True     |    False                                       |
|    False    |    True     |    True     |    False    |    False                                       |
|    False    |    True     |    True     |    True     |    False                                       |
|    True     |    False    |    False    |    False    |    False                                       |
|    True     |    False    |    False    |    True     |    False                                       |
|    True     |    False    |    True     |    False    |    False                                       |
|    True     |    False    |    True     |    True     |    False                                       |
|    True     |    True     |    False    |    False    |    False                                       |
|    True     |    True     |    False    |    True     |    False                                       |
|    True     |    True     |    True     |    False    |    False                                       |
|    True     |    True     |    True     |    True     |    False                                       |

## Question 2

### a

### b

### c

### d

## Question 3

### a
|    A        |    B        |    Not(A or B)    |    Not A and Not B    |
|-------------|-------------|-------------------|-----------------------|
|    False    |    False    |    True           |    True               |
|    False    |    True     |    False          |    False              |
|    True     |    False    |    False          |    False              |
|    True     |    True     |    False          |    False              |

### b
|    A        |    B        |    Not(A and B)    |    Not A or Not B    |
|-------------|-------------|--------------------|----------------------|
|    False    |    False    |    True            |    True              |
|    False    |    True     |    True            |    True              |
|    True     |    False    |    True            |    True              |
|    True     |    True     |    False           |    False             |

### c
|    A        |    B        |    C        |    (A and B) or (A and C)    |    A and (B or C)    |
|-------------|-------------|-------------|------------------------------|----------------------|
|    False    |    False    |    False    |    False                     |    False             |
|    False    |    False    |    True     |    False                     |    False             |
|    False    |    True     |    False    |    False                     |    False             |
|    False    |    True     |    True     |    False                     |    False             |
|    True     |    False    |    False    |    False                     |    False             |
|    True     |    False    |    True     |    True                      |    True              |
|    True     |    True     |    False    |    True                      |    True              |
|    True     |    True     |    True     |    True                      |    True              |

### d
|    A        |    B        |    C        |    (A or B) and (A or C)    |    A or (B and C)    |
|-------------|-------------|-------------|-----------------------------|----------------------|
|    False    |    False    |    False    |    False                    |    False             |
|    False    |    False    |    True     |    False                    |    False             |
|    False    |    True     |    False    |    False                    |    False             |
|    False    |    True     |    True     |    True                     |    True              |
|    True     |    False    |    False    |    True                     |    True              |
|    True     |    False    |    True     |    True                     |    True              |
|    True     |    True     |    False    |    True                     |    True              |
|    True     |    True     |    True     |    True                     |    True              |

## Question 4

### a
This problem matches the truth table for 3b. It is essentially saying if you are missing either of the files tell the user they are missing a file. The statement will only ever return false if both files are present, in which case the program will continue with whatever it is meant to do.  

### b
This problem matches the truth table for 3c. This has one imperative statement, that is that x is larger than 7 and two statements which one of which must be true, x is a float or an integer. One solution takes the essential statement on its own and independently checks the two more flexible statements. The other independently checks the or statements along with the imperative one but only one of the statements must be true. Overall returning the same values.

### c
This problem doesn’t directly respond to any of the truth tables from question 3, as the outputs have been reversed, changing a part of the equation not relevant to the truth tables. As a result, the truth tables are exact opposites of each other which baring in mind the earlier reversal proves that they produce the same output. This can be explained by 3b If you read it as Not(if X == 0 and Y == 0):, print do nothing, else:, do something and if x != 0 or y != 0:, print("Do nothing"), else:, do something. This removes the difference in output so it can be implemented into the tables proving that they provide the same output relative to the same inputs.

### d


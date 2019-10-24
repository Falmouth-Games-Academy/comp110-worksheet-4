# COMP110 Worksheet 4

Please edit this README.md file with your answers to the worksheet questions.

## Question 1

### a
|A    |B    |C    |A AND B AND NOT C|
|-----|-----|-----|-----------------|
|false|false|false|false            |
|false|false|true |false            |
|false|true |false|false            |
|false|true |true |false            |
|true |false|false|false            |
|true |false|true |false            |
|true |true |false|true             |
|true |true |true |false            |

### b
|A    |B    |C    |A AND NOT (B AND NOT C)|
|-----|-----|-----|-----------------------|
|false|false|false|false                  |
|false|false|true |false                  |
|false|true |false|false                  |
|false|true |true |false                  |
|true |false|false|true                   |
|true |false|true |true                   |
|true |true |false|false                  |
|true |true |true |true                   |

### c
|A    |B    |C    |(A OR NOT B) AND (A OR C)|
|-----|-----|-----|-------------------------|
|false|false|false|false                    |
|false|false|true |true                     |
|false|true |false|false                    |
|false|true |true |false                    |
|true |false|false|true                     |
|true |false|true |true                     |
|true |true |false|true                     |
|true |true |true |true                     |

### d
|A    |B    |C    |D    |A AND NOT (B OR NOT C) AND (NOT A AND D)|
|-----|-----|-----|-----|----------------------------------------|
|false|false|false|false|false                                   |
|false|false|false|true |false                                   |
|false|false|true |false|false                                   |
|false|false|true |true |false                                   |
|false|true |false|false|false                                   |
|false|true |false|true |false                                   |
|false|true |true |false|false                                   |
|false|true |true |true |false                                   |
|true |false|false|false|false                                   |
|true |false|false|true |false                                   |
|true |false|true |false|false                                   |
|true |false|true |true |false                                   |
|true |true |false|false|false                                   |
|true |true |false|true |false                                   |
|true |true |true |false|false                                   |
|true |true |true |true |false                                   |

## Question 2

### a
![](Logic_Circuit_A.png)

### b
![](Logic_Circuit_B.png)

### c
![](Logic_Circuit_C.png)

### d
![](Logic_Circuit_D.png)

## Question 3

### a
|A    |B    |NOT (A OR B)|
|-----|-----|------------|
|false|false|true        |
|false|true |false       |
|true |false|false       |
|true |true |false       |

|A    |B    |NOT A AND NOT B|
|-----|-----|---------------|
|false|false|true           |
|false|true |false          |
|true |false|false          |
|true |true |false          |


### b
|A    |B    |NOT (A AND B)|
|-----|-----|-------------|
|false|false|true         |
|false|true |true         |
|true |false|true         |
|true |true |false        |

|A    |B    |NOT A OR NOT B|
|-----|-----|--------------|
|false|false|true          |
|false|true |true          |
|true |false|true          |
|true |true |false         |

### c
|A    |B    |C    |(A AND B) OR (A AND C)|
|-----|-----|-----|----------------------|
|false|false|false|false                 |
|false|false|true |false                 |
|false|true |false|false                 |
|false|true |true |false                 |
|true |false|false|false                 |
|true |false|true |true                  |
|true |true |false|true                  |
|true |true |true |true                  |

|A    |B    |C    |A AND (B OR C)|
|-----|-----|-----|--------------|
|false|false|false|false         |
|false|false|true |false         |
|false|true |false|false         |
|false|true |true |false         |
|true |false|false|false         |
|true |false|true |true          |
|true |true |false|true          |
|true |true |true |true          |

### d
|A    |B    |C    |(A OR B) AND (A OR C)|
|-----|-----|-----|---------------------|
|false|false|false|false                |
|false|false|true |false                |
|false|true |false|false                |
|false|true |true |false                |
|true |false|false|false                |
|true |false|true |false                |
|true |true |false|false                |
|true |true |true |true                 |

|A    |B    |C    |A OR (B AND C)|
|-----|-----|-----|--------------|
|false|false|false|false         |
|false|false|true |false         |
|false|true |false|false         |
|false|true |true |false         |
|true |false|false|false         |
|true |false|true |false         |
|true |true |false|false         |
|true |true |true |true          |


## Question 4

### a
NOT(A and B) = NOT A or NOT b

### b
(A and C) or (B and C) = (A or B) and C

### c
A and B = NOT(NOT A or NOT B)

### d
A or (B and C) = B and (A or C)

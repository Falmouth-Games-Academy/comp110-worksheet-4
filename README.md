# COMP110 Worksheet 4

Please edit this README.md file with your answers to the worksheet questions.

## Question 1

### a
|A    |B    |C    |A AND B AND NOT C   |
|-----|-----|-----|--------------------|
|false|false|false|false               |
|false|false|true |false               |
|false|true |false|false               |
|false|true |true |false               |
|true |false|false|false               |
|true |false|true |false               |
|true |true |false|true                |
|true |true |true |false               |


### b
|A    |B    |C    |A AND NOT (B AND NOT C)  |
|-----|-----|-----|-------------------------|
|false|false|false|false                    |
|false|false|true |false                    |
|false|true |false|false                    |
|false|true |true |false                    |
|true |false|false|true                     |
|true |false|true |true                     |
|true |true |false|false                    |
|true |true |true |true                     |

### c
|A    |B    |C    |(A OR NOT B) AND (A OR C) |
|-----|-----|-----|--------------------------|
|false|false|false|false                     |
|false|false|true |true                      |
|false|true |false|false                     |
|false|true |true |false                     |
|true |false|false|true                      |
|true |false|true |true                      |
|true |true |false|true                      |
|true |true |true |true                      |

### d
|A    |B    |C    |D    |A AND NOT (B OR NOT C) AND (NOT A AND D) |
|-----|-----|-----|-----|-----------------------------------------|
|false|false|false|false|false                                    |
|false|false|false|true |false                                    |
|false|false|true |false|false                                    |
|false|false|true |true |false                                    |
|false|true |false|false|false                                    |
|false|true |false|true |false                                    |
|false|true |true |false|false                                    |
|false|true |true |true |false                                    |
|true |false|false|false|false                                    |
|true |false|false|true |false                                    |
|true |false|true |false|false                                    |
|true |false|true |true |false                                    |
|true |true |false|false|false                                    |
|true |true |false|true |false                                    |
|true |true |true |false|false                                    |
|true |true |true |true |false                                    |

## Question 2

### a
![](https://github.com/JBroughton2/comp110-worksheet-4/blob/master/Logic%20Circuit%201.PNG)

### b
![](https://github.com/JBroughton2/comp110-worksheet-4/blob/master/Logic%20Circuit%202.PNG)

### c
![](https://github.com/JBroughton2/comp110-worksheet-4/blob/master/Logic%20Circuit%203.PNG)

### d
![](https://github.com/JBroughton2/comp110-worksheet-4/blob/master/Logic%20Circuit%204.PNG)

## Question 3

### a
|A    |B    |C    |D    |NOT (A OR B)|NOT A AND NOT B|
|-----|-----|-----|-----|------------|---------------|
|false|false|false|false|true        |true           |
|false|false|false|true |true        |true           |
|false|false|true |false|true        |true           |
|false|false|true |true |true        |true           |
|false|true |false|false|false       |false          |
|false|true |false|true |false       |false          |
|false|true |true |false|false       |false          |
|false|true |true |true |false       |false          |
|true |false|false|false|false       |false          |
|true |false|false|true |false       |false          |
|true |false|true |false|false       |false          |
|true |false|true |true |false       |false          |
|true |true |false|false|false       |false          |
|true |true |false|true |false       |false          |
|true |true |true |false|false       |false          |
|true |true |true |true |false       |false          |

### b
|A    |B    |C    |D    |NOT (A AND B)|NOT A OR NOT B|
|-----|-----|-----|-----|-------------|--------------|
|false|false|false|false|true         |true          |
|false|false|false|true |true         |true          |
|false|false|true |false|true         |true          |
|false|false|true |true |true         |true          |
|false|true |false|false|true         |true          |
|false|true |false|true |true         |true          |
|false|true |true |false|true         |true          |
|false|true |true |true |true         |true          |
|true |false|false|false|true         |true          |
|true |false|false|true |true         |true          |
|true |false|true |false|true         |true          |
|true |false|true |true |true         |true          |
|true |true |false|false|false        |false         |
|true |true |false|true |false        |false         |
|true |true |true |false|false        |false         |
|true |true |true |true |false        |false         |

### c
|A    |B    |C    |D    |(A AND B) OR (A AND C)|A AND (B OR C)|
|-----|-----|-----|-----|----------------------|--------------|
|false|false|false|false|false                 |false         |
|false|false|false|true |false                 |false         |
|false|false|true |false|false                 |false         |
|false|false|true |true |false                 |false         |
|false|true |false|false|false                 |false         |
|false|true |false|true |false                 |false         |
|false|true |true |false|false                 |false         |
|false|true |true |true |false                 |false         |
|true |false|false|false|false                 |false         |
|true |false|false|true |false                 |false         |
|true |false|true |false|true                  |true          |
|true |false|true |true |true                  |true          |
|true |true |false|false|true                  |true          |
|true |true |false|true |true                  |true          |
|true |true |true |false|true                  |true          |
|true |true |true |true |true                  |true          |

### d
|A    |B    |C    |D    |(A OR B) AND (A OR C)|A OR (B AND C)|
|-----|-----|-----|-----|---------------------|--------------|
|false|false|false|false|false                |false         |
|false|false|false|true |false                |false         |
|false|false|true |false|false                |false         |
|false|false|true |true |false                |false         |
|false|true |false|false|false                |false         |
|false|true |false|true |false                |false         |
|false|true |true |false|true                 |true          |
|false|true |true |true |true                 |true          |
|true |false|false|false|true                 |true          |
|true |false|false|true |true                 |true          |
|true |false|true |false|true                 |true          |
|true |false|true |true |true                 |true          |
|true |true |false|false|true                 |true          |
|true |true |false|true |true                 |true          |
|true |true |true |false|true                 |true          |
|true |true |true |true |true                 |true          |

## Question 4

### a
|file_exists("a.txt")|file_exists("b.txt")|first program|second program|
|--------------------|--------------------|-------------|--------------|
|false               |false               |true         |true          |
|false               |true                |true         |true          |
|true                |false               |true         |true          |
|true                |true                |false        |false         |

### b
|type(x) == int|x > 7|type(x) == float|first program|second program|
|--------------|-----|----------------|-------------|--------------|
|false         |false|false           |false        |false         |
|false         |false|true            |false        |false         |
|false         |true |false           |false        |false         |
|false         |true |true            |true         |true          |
|true          |false|false           |false        |false         |
|true          |false|true            |false        |false         |
|true          |true |false           |true         |true          |
|true          |true |true            |true         |true          |

### c
|X == 0 |Y == 0|first program|second program|
|-------|------|-------------|--------------|
|true   |true  |true         |true          |
|true   |false |false        |false         |
|false  |true  |false        |false         |
|false  |false |false        |false         |
### d
|X > 10 |Y > 0 |first program|second program|
|-------|------|-------------|--------------|
|false  |false |true         |false         |
|false  |true  |true         |false         |
|true   |false |false        |false         |
|true   |true  |true         |true          |

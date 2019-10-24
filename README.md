# COMP110 Worksheet 4

## Question 1

### a
|A  |B  |C  |A AND B AND NOT C|
|F  |F  |F  |F                |
|F  |F  |T  |F                |
|F  |T  |F  |F                |
|F  |T  |T  |F                |
|T  |F  |F  |F                |
|T  |F  |T  |F                |
|T  |T  |F  |F                |
|T  |T  |T  |F                |


### b
|A |B |C |A AND NOT (B AND NOT C)|
|F |F |F |F                      |
|F |F |T |F                      |
|F |T |F |F                      |
|F |T |T |F                      |
|T |F |F |T                      |
|T |F |T |T                      |
|T |T |F |F                      |
|T |T |T |T                      |


### c
|A |B |C |(A OR NOT B) AND (A OR C)|
|F |F |F |F                        |
|F |F |T |T                        |
|F |T |F |F                        |
|F |T |T |F                        |
|T |F |F |T                        |
|T |F |T |T                        |
|T |T |F |T                        |
|T |T |T |T                        |

### d
|A |B |C |D |A AND NOT (B OR NOT C) AND (NOT A AND D)|
|F |F |F |F |F                                       |
|F |F |F |T |F                                       |
|F |F |T |F |F                                       |
|F |F |T |T |F                                       |
|F |T |F |F |F                                       |
|F |T |F |T |F                                       |
|F |T |T |F |F                                       |
|F |T |T |T |F                                       |
|T |F |F |F |F                                       |
|T |F |F |T |F                                       |
|T |F |T |F |F                                       |
|T |F |T |T |F                                       |
|T |T |F |F |F                                       |
|T |T |F |T |F                                       |
|T |T |T |F |F                                       |
|T |T |T |T |F                                       |

## Question 2

https://imgur.com/7su0dsE

## Question 3

### a
|A |B |NOT (A OR B)|
|F |F |T           |
|F |T |F           |
|T |F |F           |
|T |T |F           |

|A |B |NOT A AND NOT B|
|F |F |T              |
|F |T |F              |
|T |F |F              |
|T |T |F              |

### b
|A |B |NOT (A AND B)|
|F |F |T            |
|F |T |T            |
|T |F |T            |
|T |T |F            |


|A |B |NOT A OR NOT B|
|F |F |T             |
|F |T |T             |
|T |F |T             |
|T |T |F             |

### c
|A |B |C |(A AND B) OR (A AND C)|
|F |F |F |F                     |
|F |F |T |F                     |
|F |T |F |F                     |
|F |T |T |F                     |
|T |F |F |F                     |
|T |F |T |F                     |
|T |T |F |T                     |
|T |T |T |T                     |

|A |B |C |A AND (B OR C)|
|F |F |F |F             |
|F |F |T |F             |
|F |T |F |F             |
|F |T |T |F             |
|T |F |F |F             |
|T |F |T |T             |
|T |T |F |T             |
|T |T |T |T             |

### d
|A |B |C |(A OR B) AND (A OR C)|
|F |F |F |F                    |
|F |F |T |F                    |
|F |T |F |F                    |
|F |T |T |F                    |
|T |F |F |F                    |
|T |F |T |F                    |
|T |T |F |F                    |
|T |T |T |T                    |

|A |B |C |A OR (B AND C)|
|F |F |F |F             |
|F |F |T |F             |
|F |T |F |F             |
|F |T |T |F             |
|T |F |F |F             |
|T |F |T |F             |
|T |T |F |F             |
|T |T |T |T             |

## Question 4

### a
NOT(A and B) = NOT A or NOT b

### b
(A and C) or (B and C) = (A or B) and C

### c
A and B = NOT(NOT A or NOT B)

### d
A or (B and C) = B and (A or C)


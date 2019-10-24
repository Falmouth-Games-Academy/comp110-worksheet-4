# COMP110 Worksheet 4

## Question 1

### a

|A    |B    |C    |A AND B  |NOT C |A AND B NOT C|
|-----|-----|-----|---------|------|-------------|
|FALSE|FALSE|FALSE|FALSE    |TRUE  |FALSE        |
|FALSE|FALSE|TRUE |FALSE    |FALSE |FALSE        |
|FALSE|TRUE |FALSE|FALSE    |TRUE  |FALSE        |
|FALSE|TRUE |TRUE |FALSE    |FALSE |FALSE        |
|TRUE |FALSE|FALSE|FALSE    |TRUE  |FALSE        |
|TRUE |FALSE|TRUE |FALSE    |FALSE |FALSE        |
|TRUE |TRUE |FALSE|TRUE     |TRUE  |TRUE         |
|TRUE |TRUE |TRUE |TRUE     |FALSE |FALSE        |

### b

|A    |B    |C    |B AND NOT C |A AND NOT (B AND NOT C)|
|-----|-----|-----|------------|-----------------------|
|FALSE|FALSE|FALSE|FALSE       |FALSE                  |
|FALSE|FALSE|TRUE |FALSE       |FALSE                  |
|FALSE|TRUE |FALSE|TRUE        |FALSE                  |
|FALSE|TRUE |TRUE |FALSE       |FALSE                  |
|TRUE |FALSE|FALSE|FALSE       |TRUE                   |
|TRUE |FALSE|TRUE |FALSE       |TRUE                   |
|TRUE |TRUE |FALSE|TRUE        |FALSE                  |
|TRUE |TRUE |TRUE |FALSE       |TRUE                   |

### c

|A    |B    |C    |A OR NOT B  |A OR C                 |(A OR NOT B) AND (A OR C)|
|-----|-----|-----|------------|-----------------------|-------------------------|
|FALSE|FALSE|FALSE|TRUE        |FALSE                  |FALSE                    |
|FALSE|FALSE|TRUE |TRUE        |TRUE                   |TRUE                     |
|FALSE|TRUE |FALSE|FALSE       |FALSE                  |FALSE                    |
|FALSE|TRUE |TRUE |FALSE       |TRUE                   |FALSE                    |
|TRUE |FALSE|FALSE|TRUE        |TRUE                   |TRUE                     |
|TRUE |FALSE|TRUE |TRUE        |TRUE                   |TRUE                     |
|TRUE |TRUE |FALSE|TRUE        |TRUE                   |TRUE                     |
|TRUE |TRUE |TRUE |TRUE        |TRUE                   |TRUE                     |

### d

|A    |B    |C    |D    |NOT(B OR NOT C)|NOT A AND D| A AND NOT (B OR NOT C) AND (NOT A AND D)|
|-----|-----|-----|-----|---------------|-----------|-----------------------------------------|
|FALSE|FALSE|FALSE|FALSE|FALSE          |FALSE      |FALSE                                    |
|FALSE|FALSE|FALSE|TRUE |FALSE          |TRUE       |FALSE                                    |
|FALSE|FALSE|TRUE |FALSE|TRUE           |FALSE      |FALSE                                    |
|FALSE|FALSE|TRUE |TRUE |TRUE           |TRUE       |FALSE                                    |
|FALSE|FALSE|TRUE |TRUE |TRUE           |TRUE       |FALSE                                    |
|FALSE|TRUE |FALSE|TRUE |FALSE          |TRUE       |FALSE                                    |
|FALSE|TRUE |TRUE |FALSE|FALSE          |FALSE      |FALSE                                    |
|FALSE|TRUE |TRUE |TRUE |FALSE          |TRUE       |FALSE                                    |
|TRUE |FALSE|FALSE|FALSE|FALSE          |FALSE      |FALSE                                    |
|TRUE |FALSE|FALSE|TRUE |FALSE          |FALSE      |FALSE                                    |
|TRUE |FALSE|TRUE |FALSE|TRUE           |FASLE      |FALSE                                    |
|TRUE |FALSE|TRUE |TRUE |TRUE           |FALSE      |FALSE                                    |
|TRUE |TRUE |FALSE|FALSE|FALSE          |FALSE      |FALSE                                    |
|TRUE |TRUE |FALSE|TRUE |FALSE          |FALSE      |FALSE                                    |
|TRUE |TRUE |TRUE |FALSE|FALSE          |FALSE      |FALSE                                    |
|TRUE |TRUE |TRUE |TRUE |FALSE          |FALSE      |FALSE                                    |

## Question 2

### a
#### A AND B AND NOT C
![First_Logic_Gate](https://github.com/Koltonix/comp110-worksheet-4/blob/master/Logic_Gates_A.PNG)

### b
#### A AND NOT (B AND NOT C)
![Second_Logic_Gate](https://github.com/Koltonix/comp110-worksheet-4/blob/master/Logic_Gates_B.PNG)

### c
#### (A OR NOT B) AND (A OR C)
![Third_Logic_Gate](https://github.com/Koltonix/comp110-worksheet-4/blob/master/Logic_Gates_C.PNG)

### d
#### A AND NOT (B OR NOT C) AND (NOT A AND D)
![Fourth_Logic_Gate](https://github.com/Koltonix/comp110-worksheet-4/blob/master/Logic_Gates_D.PNG)

## Question 3

### a

|A    |B    |NOT (A OR B)|NOT A AND NOT B|
|-----|-----|------------|---------------|
|FALSE|FALSE|TRUE        |TRUE           |
|FALSE|TRUE |FALSE       |FALSE          |
|TRUE |FALSE|FALSE       |FALSE          |
|TRUE |TRUE |FALSE       |FALSE          |

### b

|A    |B    |NOT (A AND B)|NOT A OR NOT B|
|-----|-----|-------------|--------------|
|FALSE|FALSE|TRUE         |TRUE          |
|FALSE|TRUE |TRUE         |TRUE          |
|TRUE |FALSE|TRUE         |TRUE          |
|TRUE |TRUE |FALSE        |FALSE         |

### c

|A    |B    |C    |(A AND B) OR (A AND C)|A AND (B OR C)|
|-----|-----|-----|----------------------|--------------|
|FALSE|FALSE|FALSE|FALSE                 |FALSE         |
|FALSE|FALSE|TRUE |FALSE                 |FALSE         |
|FALSE|TRUE |FALSE|FALSE                 |FALSE         |
|FALSE|TRUE |TRUE |FALSE                 |FALSE         |
|TRUE |FALSE|FALSE|FALSE                 |FALSE         |
|TRUE |FALSE|TRUE |TRUE                  |TRUE          |
|TRUE |TRUE |FALSE|TRUE                  |TRUE          |
|TRUE |TRUE |TRUE |TRUE                  |TRUE          |

### d


|A    |B    |C    |(A OR B) AND (A OR C)|A OR (B AND C)|
|-----|-----|-----|---------------------|--------------|
|FALSE|FALSE|FALSE|FALSE                |FALSE         |
|FALSE|FALSE|TRUE |FALSE                |FALSE         |
|FALSE|TRUE |FALSE|FALSE                |FALSE         |
|FALSE|TRUE |TRUE |TRUE                 |TRUE          |
|TRUE |FALSE|FALSE|TRUE                 |TRUE          |
|TRUE |FALSE|TRUE |TRUE                 |TRUE          |
|TRUE |TRUE |FALSE|TRUE                 |TRUE          |
|TRUE |TRUE |TRUE |TRUE                 |TRUE          |

## Question 4

### a

|file_exists("a.txt")|file_exists("b.txt")|First Condition|Second Condition|Question 3 B|
|--------------------|--------------------|---------------|----------------|------------|
|FALSE               |FALSE               |TRUE           |TRUE            |TRUE        |
|FALSE               |TRUE                |TRUE           |TRUE            |FALSE       |
|TRUE                |FALSE               |TRUE           |TRUE            |FALSE       |
|TRUE                |TRUE                |FALSE          |FALSE           |FALSE       |

```if not(file_exists("a.txt") and file_exists("b.txt")):```

```if not file_exists("a.txt") or not file_exists("b.txt"):```

```NOT (A AND B) = NOT A OR NOT B```

### b

|type(x) == int|type(x) == float|x > 0|First Condition|Second Condition|QUESTION 3 C|
|--------------|----------------|-----|---------------|----------------|------------|
|FALSE         |FALSE           |FALSE|FALSE          |FALSE           |FALSE       |
|FALSE         |FALSE           |TRUE |FALSE          |FALSE           |FALSE       |
|FALSE         |TRUE            |FALSE|FALSE          |FALSE           |FALSE       |
|FALSE         |TRUE            |TRUE |FALSE          |FALSE           |FALSE       |
|TRUE          |FALSE           |FALSE|FALSE          |FALSE           |FALSE       |
|TRUE          |FALSE           |TRUE |TRUE           |TRUE            |TRUE        |
|TRUE          |TRUE            |FALSE|TRUE           |TRUE            |TRUE        |
|TRUE          |TRUE            |TRUE |TRUE           |TRUE            |TRUE        |

```if (type(x) == int and x > 7) or (type(x) == float  and x > 7):```

```if (type(x) == int or type(x) == float) and x > 7:```

```(A AND B) OR (A AND C) = A AND (B OR C)```

### c

|x == 0 |y == 0|First Condition|Second Condition|Question 3 B|
|-------|------|---------------|----------------|------------|
|FALSE  |FALSE |TRUE           |TRUE            |TRUE        |
|FALSE  |TRUE  |TRUE           |TRUE            |TRUE        |
|TRUE   |FALSE |TRUE           |TRUE            |TRUE        |
|TRUE   |TRUE  |FALSE          |FALSE           |FALSE       |

``` 
if x == 0 and y == 0:
  do_something ()
else:
  print("Do Nothing") 
```

```
if x != 0 or y != 0:
  print("Do Nothing")
else:
  do_something()
```

```NOT (A AND B) = NOT A OR NOT B```

### d

|x > 0|x > 10|y > 0|First Condition|Second Condition|QUESTION 3 D|
|-----|------|-----|---------------|----------------|------------|
|FALSE|FALSE |FALSE|FALSE          |FALSE           |FALSE       |
|FALSE|FALSE |TRUE |FALSE          |FALSE           |FALSE       |
|FALSE|TRUE  |FALSE|FALSE          |FALSE           |FALSE       |
|FALSE|TRUE  |TRUE |TRUE           |TRUE            |TRUE        |
|TRUE |FALSE |FALSE|TRUE           |TRUE            |TRUE        |
|TRUE |FALSE |TRUE |TRUE           |TRUE            |TRUE        |
|TRUE |TRUE  |FALSE|TRUE           |TRUE            |TRUE        |
|TRUE |TRUE  |TRUE |TRUE           |TRUE            |TRUE        |

``` 
if x > 10 or (x > 0 and y > 0):
  do_something()
```

```
if x > 0 and (x > 10 or y > 0)
  do_something()
```

```(A OR B) AND (A OR C) = A OR (B AND C)```

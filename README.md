# COMP110 Worksheet 4

Please edit this README.md file with your answers to the worksheet questions.

## Question 1

### a
| A     | B     | C     | A AND B AND NOT C |
|-------|-------|-------|-------------------|
| false | false | false | false             |
| false | false | true  | false             |
| false | true  | false | false             |
| false | true  | true  | false             |
| true  | false | false | false             |
| true  | false | true  | false             |
| true  | true  | false | true              |
| true  | true  | true  | false             |
### b
| A     | B     | C     | A AND NOT (B AND NOT C) |
|-------|-------|-------|-------------------------|
| false | false | false | false                   |
| false | false | true  | true                    |
| false | true  | false | false                   |
| false | true  | true  | false                   |
| true  | false | false | false                   |
| true  | false | true  | true                    |
| true  | true  | false | false                   |
| true  | true  | true  | true                    |
### c
| A     | B     | C     | (A OR NOT B) AND (A OR C) |
|-------|-------|-------|---------------------------|
| false | false | false | false                     |
| false | false | true  | true                      |
| false | true  | false | false                     |
| false | true  | true  | false                     |
| true  | false | false | true                      |
| true  | false | true  | true                      |
| true  | true  | false | true                      |
| true  | true  | true  | true                      |
### d
| A     | B     | C     | D     | A AND NOT (B OR NOT C) AND (NOT A AND D) |
|-------|-------|-------|-------|------------------------------------------|
| false | false | false | false | false                                    |
| false | false | false | true  | false                                    |
| false | false | true  | false | false                                    |
| false | false | true  | true  | false                                    |
| false | true  | false | false | false                                    |
| false | true  | false | true  | false                                    |
| false | true  | true  | false | false                                    |
| false | true  | true  | true  | false                                    |
| true  | false | false | false | false                                    |
| true  | false | false | true  | false                                    |
| true  | false | true  | false | false                                    |
| true  | false | true  | true  | false                                    |
| true  | true  | false | false | false                                    |
| true  | true  | false | true  | false                                    |
| true  | true  | true  | false | false                                    |
| true  | true  | true  | true  | false                                    |
## Question 2

### a
![image1](https://raw.githubusercontent.com/KalvinMalloch/comp110-worksheet-4/master/Capture.PNG)
### b
![image2](https://raw.githubusercontent.com/KalvinMalloch/comp110-worksheet-4/master/Capture2.PNG)
### c
![image3](https://raw.githubusercontent.com/KalvinMalloch/comp110-worksheet-4/master/Capture3.PNG)
### d
![image4](https://raw.githubusercontent.com/KalvinMalloch/comp110-worksheet-4/master/Capture4.PNG)
## Question 3

### a
| a     | b     | NOT (A OR B) | NOT A AND NOT B |
|-------|-------|--------------|-----------------|
| false | false | true         | true            |
| false | true  | false        | false           |
| true  | false | false        | false           |
| true  | true  | false        | false           |
### b
| a     | b     | NOT (A AND B) | NOT A OR NOT B |
|-------|-------|---------------|----------------|
| false | false | true          | true           |
| false | true  | true          | true           |
| true  | false | true          | true           |
| true  | true  | false         | false          |
### c
| a     | b     | c     | (A AND B) OR (A AND C) | A AND (B OR C) |
|-------|-------|-------|------------------------|----------------|
| false | false | false | false                  | false          |
| false | false | true  | false                  | false          |
| false | true  | false | false                  | false          |
| false | true  | true  | false                  | false          |
| true  | false | false | false                  | false          |
| true  | false | true  | true                   | true           |
| true  | true  | false | true                   | true           |
| true  | true  | true  | true                   | true           |
### d
| a     | b     | c     | (A OR B) AND (A OR C) | A OR (B AND C) |
|-------|-------|-------|-----------------------|----------------|
| false | false | false | false                 | false          |
| false | false | true  | false                 | false          |
| false | true  | false | false                 | false          |
| false | true  | true  | true                  | true           |
| true  | false | false | true                  | true           |
| true  | false | true  | true                  | true           |
| true  | true  | false | true                  | true           |
| true  | true  | true  | true                  | true           |
## Question 4

### a
| file_exists("a.txt") | file_exists("b.txt") | FIRST | SECOND |
|----------------------|----------------------|-------|--------|
| false                | false                | true  | true   |
| false                | true                 | true  | true   |
| true                 | false                | true  | true   |
| true                 | true                 | false | false  |

Same as 3(b): NOT (A AND B) = NOT A OR NOT B

### b

### c

### d


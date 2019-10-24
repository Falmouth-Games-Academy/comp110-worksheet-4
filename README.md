# COMP110 Worksheet 4

Please edit this README.md file with your answers to the worksheet questions.

## Question 1

### a

|A|B|C|A AND B AND NOT C|
|:---:|:---:|:---:|:---:|
|true|true|true|false|
|true|true|false|true|
|true|false|true|false|
|true|false|false|false|
|false|true|true|false|
|false|false|true|false|
|false|false|false|false|


### b

|A|B|C|A AND NOT (B AND NOT C)|
|:---:|:---:|:---:|:---:|
|true|true|true|true|
|true|true|false|false|
|true|false|false|true|
|true|false|true|true|
|false|true|true|false|
|false|false|true|false|
|false|false|false|false|

### c

|A|B|C|(A OR NOT B) AND (A OR C)|
|:---:|:---:|:---:|:----:|
|true|true|true|true|
|true|true|false|true|
|true|false|false|true|
|true|false|true|true|
|false|true|true|false|
|false|false|true|true|
|false|false|false|false|

### d

|A|B|C|D|A AND NOT (B OR NOT C) AND (NOT A AND D)|
|:---:|:---:|:---:|:---:|:---:|
|true|true|true|true|false|
|true|true|true|false|false|
|true|true|false|true|false|
|true|true|false|false|false|
|true|false|true|true|false|
|true|false|true|false|false|
|true|false|false|true|false|
|true|false|false|false|false|
|false|true|true|true|false|
|false|true|true|false|false|
|false|true|false|true|false|
|false|true|false|false|false|
|false|false|true|true|false|
|false|false|true|false|false|
|false|false|false|true|false|
|false|false|false|false|false|

## Question 2

### a
![](https://raw.githubusercontent.com/JD233113/comp110-worksheet-4/master/logic1.PNG)

### b
![](https://raw.githubusercontent.com/JD233113/comp110-worksheet-4/master/logic2.PNG)

### c
![](https://raw.githubusercontent.com/JD233113/comp110-worksheet-4/master/logic3.PNG)

### d
![](https://raw.githubusercontent.com/JD233113/comp110-worksheet-4/master/logic4.PNG)

## Question 3

### a
NOT (A OR B) = NOT A AND NOT B 

|A|B|RESULT|
|:---:|:---:|:---:|
|true|true|false|
|true|false|false|
|false|true|false|
|false|false|true|

### b
NOT (A AND B) = NOT A OR NOT B 

|A|B|RESULT|
|:---:|:---:|:---:|
|true|true|false|
|true|false|true|
|false|true|true|
|false|false|true|

### c
(A AND B) OR (A AND C) = A AND (B OR C)

|A|B|C|RESULT|
|:---:|:---:|:---:|:---:|
|true|true|true||
|true|true|false||
|true|false|true||
|true|false|false||
|false|true|true||
|false|true|false||
|false|false|true||
|false|false|false||

### d
(A OR B) AND (A OR C) = A OR (B AND C)

|A|B|C|RESULT|
|:---:|:---:|:---:|:---:|
|true|true|true||
|true|true|false||
|true|false|true||
|true|false|false||
|false|true|true||
|false|true|false||
|false|false|true||
|false|false|false||

## Question 4

### a

### b

### c

### d


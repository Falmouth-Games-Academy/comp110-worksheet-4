# COMP110 Worksheet 4

Please edit this README.md file with your answers to the worksheet questions.

## Question 1

### a
1a. A B  C  x
    0 0  0  0
    0 0  1  0
    0 1  0  0
    0 1  1  0
    1 0  0  0
    1 0  1  0
    1 1  0  1
    1 1  1  0

### b
1b. A B  C  x
    0 0  0  0
    0 0  1  0
    0 1  0  0
    0 1  1  0
    1 0  0  1
    1 0  1  1
    1 1  0  0
    1 1  1  1

### c
1c. A B  C  x
    0 0  0  0
    0 0  1  1
    0 1  0  0
    0 1  1  0
    1 0  0  1
    1 0  1  1
    1 1  0  0
    1 1  1  1

### d
1d. A B  C  D x
    0 0  0  1 0
    0 0  1  1 0
    0 1  0  1 0
    0 1  1  1 0
    1 0  0  1 0
    1 0  1  1 1
    1 1  0  1 0
    1 1  1  1 0
    0 0  0  0 0
    0 0  1  0 0
    0 1  0  0 0
    0 1  1  0 0
    1 0  0  0 1
    1 0  1  0 1
    1 1  0  0 1
    1 1  1  0 1

## Question 2

### a
![1a circuit](https://user-images.githubusercontent.com/56162439/67575185-ed693a80-f733-11e9-8314-b2d8450e4f12.png)


### b
![1b circuit](https://user-images.githubusercontent.com/56162439/67575700-0aead400-f735-11e9-9684-9b72a3890996.png)

### c
![1c circuit](https://user-images.githubusercontent.com/56162439/67575718-13430f00-f735-11e9-8191-a32bae8917e5.png)

### d
![1d circuit](https://user-images.githubusercontent.com/56162439/67575739-1dfda400-f735-11e9-80a8-ea4df4cea7e2.png)

## Question 3

### a
3a. A B x =  A B x
    0 0 1    0 0 1
    0 1 0    0 1 0
    1 0 0    1 0 0
	  1 1 0    1 1 0
	  Both tables above show that the identities are the same.
### b
3b. A B x =  A B x
    0 0 1    0 0 1
    0 1 1    0 1 1
    1 0 1    1 0 1
	  1 1 0    1 1 0
	Both tables above show that the identities are the same.


### c
3c. A B C x  =  A B C x
    0 0 0 0 	  0 0 0 0
    0 0 1 0     0 0 1 0
    0 1 0 0     0 1 0 0 
    0 1 1 0     0 1 1 0
    1 0 0 0     1 0 0 0
    1 0 1 1     1 0 1 1
    1 1 0 1     1 1 0 1
    1 1 1 1     1 1 1 1
	Both tables above show that the identities are the same.

### d
3d. A B C x  =  A B C x
    0 0 0 0 	  0 0 0 0
    0 0 1 0     0 0 1 0
    0 1 0 0     0 1 0 0 
    0 1 1 1     0 1 1 1
    1 0 0 1     1 0 0 1
    1 0 1 1     1 0 1 1
    1 1 0 1     1 1 0 1
    1 1 1 1     1 1 1 1
	Both tables above show that the identities are the same.

## Question 4

### a
4a. NOT(A AND B)    NOT(A OR B)
   =              =
	  A B x			      A B x
    0 0 1           0 0 1 
    0 1 1           0 1 1
    1 0 1           1 0 1
	  1 1 0           1 1 0
	After converting the program into identities and then into
	truth tables it shows how both programs are equivalent by
	having the same outputs.

### b 
(A AND B) OR (A AND B)  =  (A OR A) AND B
	A = type(x) B = x   
 	  A B x			      A B x
    0 0 0           0 0 0 
    0 1 0           0 1 0
    1 0 0           1 0 0
	  1 1 1           1 1 1
	After converting the program into identities I can read over them and tell that both identities are the same 
	but just coded out different.


### c
(A and B) = (A OR Y)
	A = x B = y    
 	  A B x			      A B x
    0 0 0           0 0 0 
    0 1 0           0 1 1
    1 0 0           1 0 1
	  1 1 1           1 1 1
	After converting the program into identities and making the truth table the results were not the same and I
	don't think the programs are equivalent.

### d
  A OR (A AND B) = A AND (A OR B)
	A = x B = y    
 	  A B x			      A B x
    0 0 0           0 0 0 
    0 1 0           0 1 0
    1 0 1           1 0 1
	  1 1 1           1 1 1
	When converting the program into an identity I can see they're both the same but switched around with the OR and
	ANDS. And to make sure I checked by making the truth table and as I expected the results are the same.

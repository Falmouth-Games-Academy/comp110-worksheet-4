# COMP110 Worksheet 4

Please edit this README.md file with your answers to the worksheet questions.

## Question 1

### a

### |  A  |  B  |  C  | A&B |A & B & not C |
### |FALSE|FALSE|FALSE|FALSE|     FALSE    |
### |FALSE|FALSE|TRUE |FALSE|     FALSE    |
### |FALSE|TRUE |FALSE|FALSE|     FALSE    |
### |FALSE|TRUE |TRUE |FALSE|     FALSE    |
### |TRUE |FALSE|FALSE|FALSE|     FALSE    |
### |TRUE |FALSE|TRUE |FALSE|     FALSE    |
### |TRUE |TRUE |FALSE|TRUE |     TRUE     |
### |TRUE |TRUE |TRUE |TRUE |     FALSE    |

### b

### |  A  |  B  |  C  | Not (B & not C) | A & not (B & not C) |
### |FALSE|FALSE|FALSE|       FALSE     |         FALSE       |
### |FALSE|FALSE|TRUE |       TRUE      |         FALSE       |
### |FALSE|TRUE |FALSE|       FALSE     |         FALSE       |
### |FALSE|TRUE |TRUE |       TRUE      |         FALSE       |
### |TRUE |FALSE|FALSE|       FALSE     |         FALSE       |
### |TRUE |FALSE|TRUE |       TRUE      |         TRUE        |
### |TRUE |TRUE |FALSE|       FALSE     |         FALSE       |
### |TRUE |TRUE |TRUE |       TRUE      |         TRUE        |

### c

### |  A  |  B  |  C  | A or not B | A or C | (A or not B) & (A or C) |
### |FALSE|FALSE|FALSE|    TRUE    |  FALSE |          FALSE          |
### |FALSE|FALSE|TRUE |    TRUE    |  TRUE  |          TRUE           |
### |FALSE|TRUE |FALSE|    FALSE   |  FALSE |          FALSE          |
### |FALSE|TRUE |TRUE |    FALSE   |  TRUE  |          FALSE          |
### |TRUE |FALSE|FALSE|    TRUE    |  TRUE  |          TRUE           |
### |TRUE |FALSE|TRUE |    TRUE    |  TRUE  |          TRUE           |
### |TRUE |TRUE |FALSE|    TRUE    |  TRUE  |          TRUE           |
### |TRUE |TRUE |TRUE |    TRUE    |  TRUE  |          TRUE           |

### d

### |  A  |  B  |  C  |  D  | Not (B or not C) | Not A and D | A & not (B or not C) & (not A and D) |
### |FALSE|FALSE|FALSE|FALSE|       FALSE      |     TRUE    |                 FALSE                |
### |FALSE|FALSE|FALSE|TRUE |       FALSE      |     TRUE    |                 FALSE                |
### |FALSE|FALSE|TRUE |FALSE|       TRUE       |     TRUE    |                 FALSE                |
### |FALSE|FALSE|TRUE |TRUE |       TRUE       |     TRUE    |                 FALSE                |
### |FALSE|TRUE |FALSE|FALSE|       FALSE      |     TRUE    |                 FALSE                |
### |FALSE|TRUE |FALSE|TRUE |       FALSE      |     TRUE    |                 FALSE                |
### |FALSE|TRUE |TRUE |FALSE|       FALSE      |     TRUE    |                 FALSE                |
### |FALSE|TRUE |TRUE |TRUE |       FALSE      |     TRUE    |                 FALSE                |
### |TRUE |FALSE|FALSE|FALSE|       FALSE      |     TRUE    |                 FALSE                |
### |TRUE |FALSE|FALSE|TRUE |       FALSE      |     FALSE   |                 FALSE                |
### |TRUE |FALSE|TRUE |FALSE|       TRUE       |     TRUE    |                 TRUE                 |
### |TRUE |FALSE|TRUE |TRUE |       TRUE       |     FALSE   |                 FALSE                |
### |TRUE |TRUE |FALSE|FALSE|       FALSE      |     TRUE    |                 FALSE                |
### |TRUE |TRUE |FALSE|TRUE |       FALSE      |     FALSE   |                 FALSE                |
### |TRUE |TRUE |TRUE |FALSE|       FALSE      |     TRUE    |                 FALSE                |
### |TRUE |TRUE |TRUE |TRUE |       FALSE      |     FALSE   |                 FALSE                |

## Question 2

### a

### b

![ques2ab](https://github.com/Heathage/comp110-worksheet-4/blob/master/2a%202b.eddx)

### c

### d

![ques2cd](https://github.com/Heathage/comp110-worksheet-4/blob/master/2c%202d.eddx)

## Question 3

### a

### |  A  |  B  |  Not (A or B)  |
### |FALSE|FALSE|       TRUE     |
### |FALSE|TRUE |       FALSE    |
### |TRUE |FALSE|       FALSE    |
### |TRUE |TRUE |       FALSE    |
### |     |     |                |
### |  A  |  B  |Not A and Not B |
### |FALSE|FALSE|       TRUE     |
### |FALSE|TRUE |       FALSE    |
### |TRUE |FALSE|       FALSE    |
### |TRUE |TRUE |       FALSE    |

### b

### |  A  |  B  |  Not (A & B)  |
### |FALSE|FALSE|      TRUE     |
### |FALSE|TRUE |      TRUE     |
### |TRUE |FALSE|      TRUE     |
### |TRUE |TRUE |      FALSE    |
### |     |     |               |
### |  A  |  B  |Not A or Not B |
### |FALSE|FALSE|      TRUE     |
### |FALSE|TRUE |      TRUE     |
### |TRUE |FALSE|      TRUE     |
### |TRUE |TRUE |      FALSE    |

### c

### |  A  |  B  |  C  |   A and B  | A and C | (A and B) or (A and C) |
### |FALSE|FALSE|FALSE|    FALSE   |  FALSE  |          FALSE          |
### |FALSE|FALSE|TRUE |    FALSE   |  FALSE  |          FALSE          |
### |FALSE|TRUE |FALSE|    FALSE   |  FALSE  |          FALSE          |
### |FALSE|TRUE |TRUE |    FALSE   |  FALSE  |          FALSE          |
### |TRUE |FALSE|FALSE|    FALSE   |  FALSE  |          FALSE          |
### |TRUE |FALSE|TRUE |    FALSE   |  TRUE   |          TRUE           |
### |TRUE |TRUE |FALSE|    TRUE    |  FALSE  |          TRUE           |
### |TRUE |TRUE |TRUE |    TRUE    |  TRUE   |          TRUE           |

### |  A  |  B  |  C  |            | B or C |       A and (B or C)     |
### |FALSE|FALSE|FALSE|            |  FALSE |           FALSE          |
### |FALSE|FALSE|TRUE |            |  TRUE  |           FALSE          |
### |FALSE|TRUE |FALSE|            |  TRUE  |           FALSE          |
### |FALSE|TRUE |TRUE |            |  TRUE  |           FALSE          |
### |TRUE |FALSE|FALSE|            |  FALSE |           FALSE          |
### |TRUE |FALSE|TRUE |            |  TRUE  |           TRUE           |
### |TRUE |TRUE |FALSE|            |  TRUE  |           TRUE           |
### |TRUE |TRUE |TRUE |            |  TRUE  |           TRUE           |

### d

### |  A  |  B  |  C  | A or B | A or C | (A or B) & (A or C) |
### |FALSE|FALSE|FALSE|  FALSE |  FALSE |        FALSE        |
### |FALSE|FALSE|TRUE |  FALSE |  TRUE  |        FALSE        |
### |FALSE|TRUE |FALSE|  TRUE  |  FALSE |        FALSE        |
### |FALSE|TRUE |TRUE |  TRUE  |  TRUE  |        TRUE         |
### |TRUE |FALSE|FALSE|  TRUE  |  TRUE  |        TRUE         |
### |TRUE |FALSE|TRUE |  TRUE  |  TRUE  |        TRUE         |
### |TRUE |TRUE |FALSE|  TRUE  |  TRUE  |        TRUE         |
### |TRUE |TRUE |TRUE |  TRUE  |  TRUE  |        TRUE         |

### |  A  |  B  |  C  |        | B & C |      A or (B & C)    |
### |FALSE|FALSE|FALSE|        | FALSE |         FALSE        |
### |FALSE|FALSE|TRUE |        | FALSE |         FALSE        |
### |FALSE|TRUE |FALSE|        | FALSE |         FALSE        |
### |FALSE|TRUE |TRUE |        | TRUE  |         TRUE         |
### |TRUE |FALSE|FALSE|        | FALSE |         TRUE         |
### |TRUE |FALSE|TRUE |        | FALSE |         TRUE         |
### |TRUE |TRUE |FALSE|        | FALSE |         TRUE         |
### |TRUE |TRUE |TRUE |        | TRUE  |         TRUE         |

## Question 4

### a

### The two programs are equivalent because they follow the same logic as the truth table that I presented in Question 3a. The first code listing is printing a text line if theres no a.txt and no b.txt which is another way of saying NOT A AND NOT B. The second code listing is printing a text line if a.txt or b.txt doesn't exist which is another way of putting NOT(A OR B). Applying these to a truth table as like I did before, you can see the same outputs for both.

### b


### c

### d

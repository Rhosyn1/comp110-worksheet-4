# COMP110 Worksheet 4

Please edit this README.md file with your answers to the worksheet questions.

## Question 1

### a

| A | B | C | NOT C   | A AND B | A AND B AND NOT C |
|---|---|---|---------|---------|-------------------|
| 0 | 0 | 0 |    1    |    0    | 0                 |
| 1 | 1 | 1 |    0    |    1    | 0                 |
| 1 | 1 | 0 |    1    |    1    | 1                 |
| 1 | 0 | 0 |    1    |    0    | 0                 |
| 0 | 1 | 1 |    0    |    0    | 0                 |
| 0 | 0 | 1 |    0    |    0    | 0                 |
| 1 | 0 | 1 |    0    |    0    | 0                 |
| 0 | 1 | 0 |    1    |    0    | 0                 |


### b
|    A    |    B    |    C    |  NOT B  |  NOT C  |  A AND NOT (B AND NOT C) |
|---------|---------|---------|---------|---------|--------------------------|
|    0    |    0    |    0    |    1    |    1    |    0                     |
|    1    |    1    |    1    |    0    |    0    |    0                     |
|    1    |    1    |    0    |    0    |    1    |    0                     |
|    1    |    0    |    0    |    1    |    1    |    1                     |
|    0    |    1    |    1    |    0    |    0    |    0                     |
|    0    |    0    |    1    |    1    |    0    |    0                     |
|    1    |    0    |    1    |    1    |    0    |    0                     |
|    0    |    1    |    0    |    0    |    1    |    0                     |
### c
|    A    |    B    |    C    |   NOT B    |   A OR NOT B |   A OR C |   (A OR NOT B) AND (A OR C) |
|---------|---------|---------|------------|--------------|----------|-----------------------------|
|    0    |    0    |    0    |    1       |    1         |    0     |    0                        |
|    1    |    1    |    1    |    0       |    1         |    1     |    1                        |
|    1    |    1    |    0    |    0       |    1         |    1     |    1                        |
|    1    |    0    |    0    |    1       |    1         |    1     |    1                        |
|    0    |    1    |    1    |    0       |    0         |    1     |    0                        |
|    0    |    0    |    1    |    1       |    1         |    1     |    1                        |
|    1    |    0    |    1    |    1       |    1         |    1     |    1                        |
|    0    |    1    |    0    |    0       |    0         |    0     |    0                        |
### d
|    A    |    B    |    C    |    D    |  NOT B   |   NOT C |  NOT A   |   NOT(B OR NOT C) |   NOT A AND D |   A AND NOT(B OR NOT C) AND (NOT A AND D) |
|---------|---------|---------|---------|----------|---------|----------|-------------------|---------------|-------------------------------------------|
|    0    |    0    |    0    |    0    |    1     |    1    |    1     |    1              |    0          |    0                                      |
|    1    |    1    |    1    |    1    |    0     |    0    |    0     |    0              |    0          |    0                                      |
|    1    |    1    |    1    |    0    |    0     |    0    |    0     |    0              |    0          |    0                                      |
|    1    |    1    |    0    |    0    |    0     |    1    |    0     |    1              |    0          |    0                                      |
|    1    |    0    |    0    |    0    |    1     |    1    |    0     |    1              |    0          |    0                                      |
|    0    |    1    |    1    |    1    |    0     |    0    |    1     |    0              |    1          |    0                                      |
|    0    |    0    |    1    |    1    |    1     |    0    |    1     |    1              |    1          |    0                                      |
|    0    |    0    |    0    |    1    |    1     |    1    |    1     |    1              |    1          |    0                                      |
|    0    |    1    |    1    |    0    |    0     |    0    |    1     |    0              |    0          |    0                                      |
|    1    |    0    |    0    |    1    |    1     |    1    |    0     |    1              |    1          |    1                                      |
|    0    |    1    |    0    |    0    |    0     |    1    |    1     |    1              |    0          |    0                                      |
|    0    |    0    |    1    |    0    |    1     |    0    |    1     |    1              |    0          |    0                                      |
## Question 2

![Logic Circuits](https://user-images.githubusercontent.com/56129572/67520335-8b132a00-f6a0-11e9-9601-f4858f6e55fa.png)


## Question 3

### a
|    A    |    B    |   NOT A |   NOT B |   NOT(A OR B) |   NOT A AND NOT B |
|---------|---------|---------|---------|---------------|-------------------|
|    0    |    0    |    1    |    1    |    1          |    1              |
|    0    |    1    |    1    |    0    |    0          |    0              |
|    1    |    0    |    0    |    1    |    0          |    0              |
|    1    |    1    |    0    |    0    |    0          |    0              |
### b

|    A    |    B    |  NOT A  |   NOT B |  NOT(A AND B) |   NOT A OR NOT B |
|---------|---------|---------|---------|---------------|------------------|
|    0    |    0    |    1    |    1    |    1          |    1             |
|    1    |    0    |    0    |    1    |    1          |    1             |
|    0    |    1    |    1    |    0    |    1          |    1             |
|    1    |    1    |    0    |    0    |    0          |    0             |

### c

|    A    |    B    |    C    |    A AND B    |   A AND C    |   B OR C |   (A AND B) OR (A AND C)    |    A AND (B OR C)   |
|---------|---------|---------|--------------|-------------|-----------|---------------------|---------------|
|    0    |    0    |    0    |    0         |    0        |    0      |    0                |    0          |
|    1    |    1    |    1    |    1         |    1        |    1      |    1                |    1          |
|    1    |    1    |    0    |    1         |    0        |    1      |    1                |    1          |
|    1    |    0    |    0    |    0         |    0        |    0      |    0                |    0          |
|    0    |    1    |    1    |    0         |    0        |    1      |    0                |    0          |
|    0    |    0    |    1    |    0         |    0        |    1      |    0                |    0          |
|    1    |    0    |    1    |    0         |    1        |    1      |    1                |    1          |
|    0    |    1    |    0    |    0         |    0        |    1      |    0                |    0          |

### d

|    A    |    B    |    C    |   A OR B |   A OR C |   B AND C |  (A OR B) AND (A OR C)    |   A OR (B AND C) |
|---------|---------|---------|----------|----------|-----------|---------------------------|------------------|
|    0    |    0    |    0    |    0     |    0     |    0      |    0                      |    0             |
|    1    |    1    |    1    |    1     |    1     |    1      |    1                      |    1             |
|    1    |    1    |    0    |    1     |    1     |    0      |    1                      |    1             |
|    1    |    0    |    0    |    1     |    1     |    0      |    1                      |    1             |
|    0    |    1    |    1    |    1     |    1     |    1      |    1                      |    1             |
|    0    |    0    |    1    |    0     |    1     |    0      |    0                      |    0             |
|    1    |    0    |    1    |    1     |    1     |    0      |    1                      |    1             |
|    0    |    1    |    0    |    0     |    0     |    0      |    0                      |    0             |

## Question 4

### a
From DeMorgan’s Law, not (a.b) = not a or not b
### b
DeMorgan’s Law, x(int) and x>7 or x (float) and x > 7 == x(int) or x(float) and x > 7
### c
if x and y were both equal to 0 then the function do_something() would run but if x and y weren’t both equal to 0 then “do nothing” would be outputted so if x or y is not equal to 0 then nothing would be outputted and if they were both equal to 0 then do_something() would run.
### d
if x is more than 10 or (x is more than 0 and y is more than 0) then do_something() will run, so if x is more than  0 and (x is more than 10 or y is more than 0) then do_something() would run. In both it’s checking if x is more than 10, and x needs to be more than 10 in both for do_something() to run. 

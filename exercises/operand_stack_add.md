# Adding two numbers using operand stack
Write a program for adding integers of any size.

-----

## Example:                                            
```
                                                         1
   592               2                 9                 5                 1
+ 3784             + 4               + 8               + 7               + 3
------             ---               ---               ---               ---
  4376               6                17                13                 4
                                                                                         
operand-stack1 | |               | |               | |               | |               | |
               |2|----+          | |               | |               | |               | |
               |9|    |          |9|----+          | |               | |               | |
               |5|    |          |5|    |   +---+  |5|----+   +---+  | |               | |
                      |                 |   |   |         |   |   |
                      +-> 6             +-> 17  +---------+-> 13  +---------+-> 4
                      |   |             |    |            |    |            |   |
operand-stack2 |4|----+   |      | |    |    |     | |    |    |     | |    |   |      | |
               |8|        |      |8|----+    |     | |    |    |     | |    |   |      | |
               |7|        |      |7|         |     |7|----+    |     | |    |   |      | |
               |3|        |      |3|         |     |3|         |     |3|----+   |      | |
                          |                  |                 |                |                
                          |                  |                 |                |
                          |                  |                 |                |
result-stack   | |        |      | |         |     | |         |     | |        +----->|4|
               | |        |      | |         |     | |         +---->|3|               |3|
               | |        |      | |         +---->|7|               |7|               |7|
               | |        +----->|6|               |6|               |6|               |6|
```

-----

## Input:
Two integers

-----

## Output:
Result of the addition
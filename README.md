# COBOL Logic Error: Table Update
This repository demonstrates a common logic error in COBOL programs involving table updates. The program processes a table (WS-TABLE), but its logic for handling values exceeding a certain limit (100) is flawed.

## Bug Description:
The `PROCEDURE DIVISION` contains a loop that iterates through the `WS-TABLE`. It updates `WS-VALUE` and checks if the value exceeds 100. However, there is a risk of exceeding the maximum value of `WS-VALUE`, which will lead to unexpected results. 

## Bug Solution:
The `bugSolution.cob` file shows the corrected code. The solution focuses on the correct handling of exceeding the value 100 within the loop.

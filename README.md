# Stack
Stack Data type written in C

A 'Stack' is a FILO data type used in widely in applications such as back buttons and browser histroy. Overall a very useful data type that can be used in a lot of creative ways.

The Stack is made with a struct with members 'array', 'MIN', 'MAX' and 'nextFree'.
The functions in the program are:

Push(stackName, value): If the stack is not full then makes the index at **nextFree** equal to **value**.
Pop(stackName): If the stack is not empty, then minuses 1 from **nextFree** member and returns the value that **nextFree** was pointing to.
Peak(stackName): if the stack is not empty, returns the value at the top of the stack(The index **nextFree** points to).
Inisialize_Array(stackName, lengthOfArray): Makes arr[0] equal to the **lengthOfArray** and then makes your **lengthOfArray** after it all 0;
Output_Array(arr, size): Outputs to console the contents of the array without popping values off the stack.
Check_Empty(stackName): Checks if stack is empty.
Check_Full(stackName): Checks if stack is full.

### The debugger
- stops at breakpoints, untill all the code required by each breakpoints has finished.
- Operations: 
    - Continue: continues the code, to finish current breakpoint, and **stops at the next breakpoint**
    - Step Over: go to the **next line** of code.
    - Step Into: go **into the function** at the **current line** of code
    - Step Out: Go **out of the local function**, back to the **before line** of code.
### The call stack
- Is the different places (functions, classes, modules, etc.) outside of current breakpoint.
- Will tell you how the breakpoint calls other functions, and how those functions call others as well.

### Watch
- Write an expression, it will show changes of that expression everytime a step is made.

### Variables
- Show changes in Global and Local variables (when the steps are in a particular class or function).
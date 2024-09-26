```mermaid
flowchart LR
 Start([Start]) --> U(User input)
 U -->R(Random num generator)
 R -->O(Output)
 O -->C(Correct) & I(Incorrect)
 I -->R
 End([End])
```

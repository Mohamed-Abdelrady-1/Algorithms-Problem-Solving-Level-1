## Set 4: Functions & Structures (Problems 31-40)
Transitions to building complete mini-systems using structured data, modular functions, and optimized logic.

| #  | Problem Name | Solution | Concepts & Topics |
| :- | :--- | :--- | :--- |
| 31 | Power of 2, 3, 4 | [View](04_Functions_and_Structs/31_Power_Of_2_3_4.cpp) | `Math`, `Functions`, `Overloading Logic` |
| 32 | Power Function | [View](04_Functions_and_Structs/32_Power_Function.cpp) | `Loops`, `Structs`, `Math` |
| 33 | Grade Checker | [View](04_Functions_and_Structs/33_Grade_Checker.cpp) | `If-Else`, `Validation`, `Range Checking` |
| 34 | Commission Calculator | [View](04_Functions_and_Structs/34_Commission_Calculator.cpp) | `Business Logic`, `Tiers`, `Conditionals` |
| 35 | Piggy Bank System | [View](04_Functions_and_Structs/35_Piggy_Bank_Calculator.cpp) | `Structs`, `Constants`, `Currency Conversion` |
| 36 | Simple Calculator | [View](04_Functions_and_Structs/36_Simple_Calculator.cpp) | `Enums`, `Switch Case`, `UX` |
| 37 | Sum Until Stop | [View](04_Functions_and_Structs/37_Sum_Until_Stop.cpp) | `Sentinel Value`, `Stream Processing`, `Loops` |
| 38 | Prime Check (Optimized) | [View](04_Functions_and_Structs/38_Prime_Check.cpp) | `Algorithms`, `Optimization`, `Enums` |
| 39 | Pay Remainder | [View](04_Functions_and_Structs/39_Pay_Remainder.cpp) | `Financial Logic`, `Transaction Validation` |
| 40 | Service Fee & Tax | [View](04_Functions_and_Structs/40_Service_Fee_and_Tax.cpp) | `Cascading Logic`, `Constants`, `Math` |

#### Logic Highlights

**1. Optimized Prime Check (Problem 38):**
Using logical division to reduce complexity to O(√N) without using `sqrt()` function or causing overflow.
```cpp
enPrim_NotPrime Check_Prime_Number(int Number)
{
    // Optimization: Check until Number / Counter to avoid overflow
    for (int Counter = 2; Counter <= Number / Counter; Counter++)
    {
        if (Number % Counter == 0)
            return enPrim_NotPrime::Not_Prime;
    }
    return enPrim_NotPrime::Prime;
}
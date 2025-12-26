# Set 1: Basics, Structures & Enums (Problems 1-10) 💻

This folder contains the first 10 solutions, focusing on building program structure, handling data types, and using user-defined types like **Structs** and **Enums**.

## 📂 Problem List & File Names

|   #    | File Name                           | Description & Concepts                                                               |
| :----: | :---------------------------------- | :----------------------------------------------------------------------------------- | --- | --- |
| **01** | `01_Print_Name.cpp`                 | **Print Name**: Basic Output using `cout`.                                           |
| **02** | `02_Read_User_Name.cpp`             | **Read Name**: Input handling with `getline` and `cin`.                              |
| **03** | `03_Check_Odd_Or_Even.cpp`          | **Odd/Even Check**: Using `enum` for type safety & Modulo operator.                  |
| **04** | `04_Hire_Driver_Basic.cpp`          | **Hire Driver (v1)**: Using `struct` for User Info & Logical AND `&&`.               |
| **05** | `05_Hire_Driver_Recommendation.cpp` | **Hire Driver (v2)**: Complex Logic with `struct` (Handling Recommendations `        |     | `). |
| **06** | `06_Full_Name_Reversal.cpp`         | **Name Reversal**: String concatenation & Conditional Logic based on `struct` input. |
| **07** | `07_Calculate_Half_Number.cpp`      | **Half Number**: Breaking down logic into reusable `functions`.                      |
| **08** | `08_Check_Mark_Pass_Fail.cpp`       | **Pass/Fail Check**: Using `enum` (Pass/Fail) for clearer return values.             |
| **09** | `09_Sum_Numbers_Array.cpp`          | **Sum 3 Numbers**: Introduction to `Arrays` and `do-while` loops.                    |
| **10** | `10_Average_Marks_Array.cpp`        | **Average Calculation**: `Array` iteration & code reusability (Sum function).        |

## 💡 Code Highlights

### 1. Structs for Data Management (Problem 05)

Instead of passing multiple variables, I grouped related data (Age, License, Recommendation) into a single `struct`:

```cpp
struct stUser_Information
{
    short Age;
    bool HasDrivingLicense;
    bool HasRecommendation;
};
```

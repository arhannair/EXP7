# Experiment 7: Study of Loops in Python

**Name:** Arhan Nair

**Roll No:** 25070123169

## 1. Theory

### Introduction to Loops

In Python, loops are control structures used to repeat a specific block of code multiple times. This is essential for tasks that require automation, processing collections of data, or performing repetitive mathematical calculations.

### Types of Loops

The two primary types of loops studied in this experiment are:

1. **While Loop:** This loop repeats a block of code as long as a specified Boolean condition remains `True`. It is generally used when the number of iterations is not known beforehand.
* **Syntax:**
```python
while condition:
    # code block

```




2. **For Loop:** Used for iterating over a sequence (such as a list, tuple, dictionary, set, or string).
3. **Nested Loops:** A loop placed inside another loop.

### Loop Control Statements

Control statements change the execution of a loop from its normal sequence:

* **break:** Terminates the loop statement and transfers execution to the statement immediately following the loop.
* **continue:** Causes the loop to skip the remainder of its body and immediately retest its condition prior to reiterating.
* **else (with loops):** Python allows an optional `else` block after a loop, which executes only if the loop terminates naturally (without a `break`).

---

## 2. Algorithms

### 1. Print Numbers from 1 to 5

1. **Start**
2. Initialize .
3. While :
* Print .
* Increment  by .


4. **Stop**

### 2. Factorial of a Number

1. **Start**
2. Input an integer .
3. Initialize .
4. If , print "Factorial does not exist".
5. Else, while :
* .
* .


6. Print the value of .
7. **Stop**

### 3. Fibonacci Series (n terms)

1. **Start**
2. Input number of terms .
3. Initialize , , and .
4. While :
* Print .
* Calculate .
* Update  and .
* Increment .


5. **Stop**

### 4. Palindrome Check

1. **Start**
2. Input a number or string.
3. Create a reversed copy of the input.
4. Compare the original with the reversed version.
5. If they match, print "Palindrome"; else, print "Not Palindrome".
6. **Stop**

### 5. Search Element in a List (Break)

1. **Start**
2. Define list `nums`.
3. While :
* If `nums[i]` matches the key, print the index and **break**.
* Increment .


4. If not found after the loop, print "element not found".
5. **Stop**

---

## 3. Conclusion

This experiment illustrates the versatility of **iterative control structures** in Python. The `while` loop serves as a fundamental tool for executing a block of code repeatedly as long as a specific condition remains true.

Key insights from this study include:

* **Loop Control**: The use of `break` allows for immediate termination when a condition is met, while `continue` allows for skipping specific iterations.
* **Mathematical Logic**: Loops are essential for implementing sequences such as factorials, Fibonacci series, and digit-based operations like reversing numbers.
* **Data Validation**: Iteration is a key component in validating data types like palindromes, where elements must be compared systematically.
* **Efficiency**: Pythonic techniques like string slicing (`[::-1]`) provide efficient alternatives to loops for specific reversal tasks.

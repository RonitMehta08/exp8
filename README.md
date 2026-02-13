#  Study of For Loop in Python


##  Experiment Details

|  File |  Experiment |
|--------|--------------|
| **exp8.ipynb** | **For Loop in Python** |

---

##  Aim
 To study and implement the **for loop in Python**.

---

##  Theory

A **for loop** is a control flow statement used to repeatedly execute a block of code for a fixed number of times or over a sequence such as a list, tuple, string, or range.

Unlike while loops, **for loops are preferred when the number of iterations is known beforehand**, making them simpler and less error-prone.

### 🔹 Key Characteristics:
- Iterates over sequences automatically  
- Reduces the chances of infinite loops  
- Improves readability of code  
- Commonly used in algorithms, matrix operations, and pattern generation  

---

##  Types of For Loop Operations Covered

🔹 **Range-Based Iteration**  
Used to execute a loop a specific number of times.

🔹 **Nested Loops**  
A loop inside another loop, useful for matrix operations and pattern printing.

🔹 **Accumulator Pattern**  
Used for calculations such as sums.

🔹 **Loop Control with `break`**  
Helps terminate loops when a condition is satisfied.

---

#  Algorithm (Cell-wise)

---

## 🔹 Cell 1 – Print Numbers from 1 to 5
**Algorithm:**
1. Start the program.  
2. Use `range(1,6)` to generate numbers from 1 to 5.  
3. Iterate through the range using a for loop.  
4. Print each number.  
5. End the program.  

---

## 🔹 Cell 2 – Print Only Odd Numbers from 1 to 10
**Algorithm:**
1. Begin execution.  
2. Use `range(1,11,2)` where the step value `2` skips even numbers.  
3. Iterate through the range.  
4. Print each odd number.  
5. Stop execution.  

---

## 🔹 Cell 3 – Sum of First N Numbers
**Algorithm:**
1. Start the program.  
2. Prompt the user to enter a number `n`.  
3. Initialize `total = 0`.  
4. Use a for loop from `1` to `n`.  
5. Add each number to `total`.  
6. Display the final sum.  
7. Terminate execution.  

---

## 🔹 Cell 4 – Display a 3×3 Matrix
**Algorithm:**
1. Begin the program.  
2. Define a 3×3 matrix using nested lists.  
3. Use a nested for loop:
   - Outer loop controls rows.  
   - Inner loop controls columns.  
4. Print each element with spacing.  
5. Move to the next line after each row.  
6. End the program.  

---

## 🔹 Cell 5 – Multiplication of Two 3×3 Matrices
**Algorithm:**
1. Start execution.  
2. Define matrices `A` and `B`.  
3. Initialize a result matrix with zeros.  
4. Use three nested loops:
   - Outer loop for rows of `A`.  
   - Middle loop for columns of `B`.  
   - Inner loop for multiplication and addition.  
5. Compute each element using:  
   `Result[i][j] += A[i][k] * B[k][j]`  
6. Print the resultant matrix row-wise.  
7. Stop execution.  

---

## 🔹 Cell 6 – Print All Prime Numbers in a Range
**Algorithm:**
1. Begin the program.  
2. Iterate numbers from `2` to `50`.  
3. For each number, check divisibility from `2` to `num-1`.  
4. If divisible, terminate the inner loop using `break`.  
5. If no divisor is found, the number is prime.  
6. Print the prime number.  
7. End execution.  

---

## 🔹 Cell 7 – Inverted Star Pattern
**Algorithm:**
1. Start the program.  
2. Use a loop from `5` down to `1`.  
3. Print `"* "` repeated `i` times in each iteration.  
4. Move to the next line after each row.  
5. Stop execution.  

---

## 🔹 Cell 8 – Right-Aligned Pyramid Pattern
**Algorithm:**
1. Begin execution.  
2. Set the number of rows (e.g., `5`).  
3. Iterate from `1` to the number of rows.  
4. Print spaces to create right alignment.  
5. Print `"* "` repeated `i` times.  
6. Continue until the pyramid is formed.  
7. End the program.  

---

#  Conclusion

This experiment demonstrates the importance of **for loops** in writing efficient and structured Python programs.

- For loops simplify iteration over sequences.  
- Nested loops enable matrix computations and pattern generation.  
- They help implement mathematical algorithms efficiently.  
- For loops improve code readability and reduce logical errors.  
- Mastering for loops is fundamental for advanced programming concepts such as data structures and algorithm design.

# Experiment 7: Study of Loops in Python

Name: Saumya
PRN: 25070123161

AIM : To understand and implement looping concepts in Python using while loops through different programs such as number printing, factorial, Fibonacci series, palindrome checking, and searching elements.

while loop : A while loop is a control structure in programming that repeatedly executes a block of code as long as a given condition is true.

It checks the condition before every iteration, and the loop continues until the condition becomes false.

## Programs and Algorithms

### 1. Print numbers less than 6

**Algorithm:**

1. Start
2. Initialize variable `i = 1`
3. While `i < 6`

   * Print `i`
   * Increment `i` by 1
4. Stop

---

### 2. Print numbers from 1 to N

**Algorithm:**

1. Start
2. Input value `N`
3. Initialize `i = 1`
4. While `i ≤ N`

   * Print `i`
   * Increment `i`
5. Stop

---

### 3. Factorial of a number

**Algorithm:**

1. Start
2. Input number `n`
3. Initialize `fact = 1`, `i = 1`
4. While `i ≤ n`

   * `fact = fact × i`
   * Increment `i`
5. Print `fact`
6. Stop

---

### 4. Fibonacci series (N terms)

**Algorithm:**

1. Start
2. Input number of terms `n`
3. Initialize `a = 0`, `b = 1`, `count = 0`
4. While `count < n`

   * Print `a`
   * `c = a + b`
   * `a = b`, `b = c`
   * Increment `count`
5. Stop

---

### 5. Fibonacci series within a limit

**Algorithm:**

1. Start
2. Input limit `L`
3. Initialize `a = 0`, `b = 1`
4. While `a ≤ L`

   * Print `a`
   * `c = a + b`
   * `a = b`, `b = c`
5. Stop

---

### 6. Reverse a number

**Algorithm:**

1. Start
2. Input number `num`
3. Initialize `rev = 0`
4. While `num > 0`

   * `digit = num % 10`
   * `rev = rev × 10 + digit`
   * `num = num // 10`
5. Print `rev`
6. Stop

---

### 7. Check palindrome number

**Algorithm:**

1. Start
2. Input number `num`
3. Store original number
4. Reverse the number using loop
5. If reversed number equals original

   * Print palindrome
     Else
   * Print not palindrome
6. Stop

---

### 8. Check palindrome string (fixed value)

**Algorithm:**

1. Start
2. Assign string = “madam”
3. Reverse string
4. Compare original and reversed
5. If equal → palindrome
   Else → not palindrome
6. Stop

---

### 9. Check palindrome string (user input)

**Algorithm:**

1. Start
2. Input string
3. Reverse string
4. Compare both strings
5. Display result
6. Stop

---

### 10. Count digits in a number

**Algorithm:**

1. Start
2. Input number `num`
3. Initialize `count = 0`
4. While `num > 0`

   * `num = num // 10`
   * Increment `count`
5. Print `count`
6. Stop

---

### 11. Search an element in a list

**Algorithm:**

1. Start
2. Input list elements
3. Input element to search
4. Initialize index `i = 0`
5. While `i < length of list`

   * If element found → print index and stop
   * Else increment `i`
6. If not found → print message
7. Stop

---

### 12. Print odd numbers from 1 to 10

**Algorithm:**

1. Start
2. Initialize `i = 1`
3. While `i ≤ 10`

   * If `i` is even → increment and continue
   * Else print `i`
   * Increment `i`
4. Stop

#CONCLUSION : We get to learn about while loop






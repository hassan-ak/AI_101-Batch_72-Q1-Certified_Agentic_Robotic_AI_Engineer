# 🐍 Python Crash Course: Assignment (Chapters 2–4)

> 📘 Based on *Python Crash Course* by Eric Matthes (Chapters 2 to 4)

---

## ✨ Part 1: Variables & Input

### ✅ Q1. Favorite Movie Intro

* Ask the user for:

  * Their name
  * Their favorite movie
* Print a sentence like:
  `Ali’s favorite movie is Interstellar.`

---

### ✅ Q2. Case Converter

* Ask the user to enter a word.
* Print:

  * The word in uppercase
  * The word in lowercase
  * The word in title case

---

### ✅ Q3. Simple Math with Input

* Ask the user to input two numbers using `input()`
* Convert them to `int` or `float`
* Print:

  * Sum
  * Difference
  * Product
  * Quotient

```python
# Sample Output:
Enter first number: 5  
Enter second number: 2  

Sum: 7  
Difference: 3  
Product: 10  
Quotient: 2.5  
```

---

## 📋 Part 2: Lists & Indexing

### ✅ Q4. My Friends List

* Create a list of 4 friends’ names.
* Print each name using a `for` loop.

---

### ✅ Q5. Update Your List

1. Create a list of 3 favorite fruits.
2. Replace the second fruit with another.
3. Add one fruit to the end using `.append()`.
4. Add one to the beginning using `.insert(0, ...)`.
5. Print the list after each change.

---

### ✅ Q6. List Length Reporter

1. Ask the user to enter 5 favorite animals (use `input()`).
2. Store each animal in a list.
3. After collecting:

   * Print the total number of animals using `len()`
   * Print the first and last animal using indexing

---

## 🔁 Part 3: For Loops & Ranges

### ✅ Q7. Print Numbers

Use `range()` and `for` loop to:

* Print numbers from 1 to 10
* Print even numbers from 2 to 20
* Print multiples of 5 from 5 to 50

---

### ✅ Q8. Squares Table

Use a `for` loop to print square numbers from 1 to 10:

```text
1 squared is 1  
2 squared is 4  
3 squared is 9  
...  
10 squared is 100  
```

---

## 🧠 Part 4: List Comprehension & Slicing

### ✅ Q9. Make a List of Cubes

* Use **list comprehension** to generate cubes of numbers 1–5.
* Print the list.

```python
# Output:
[1, 8, 27, 64, 125]
```

---

### ✅ Q10. Top 3 Movies

1. Ask the user to enter 5 movie names using `input()`.
2. Store them in a list.
3. Print:

   * The first 3 movies using slicing
   * The last 2 movies using slicing

---

### ✅ Q11. 🧑‍🏫 Top Students

1. Ask the user to enter names of **5 students** using `input()` (one by one).
2. Store the names in a list.
3. Then:

   * Print a **greeting** for each student using a `for` loop.
   * Print only the **top 3 students** using slicing.
   * Copy the list using `[:]`, then:

     * Add 2 new names to the copied list using `.append()`
     * Print both the original and the new list to show that the original is unchanged.

---

### ✅ Q12. ✈️ Travel Wishlist

1. Create a list of 5 places you want to visit.
2. Print the **original list**.
3. Print a **temporarily sorted list** using `sorted()`.
4. Sort the list in **reverse alphabetical order** using `.sort(reverse=True)`.
5. Use `.reverse()` twice:

   * First to flip and print the list
   * Then to flip it back and print again

---

## 🎯 Mini Challenge: Name Art Generator

> Combine your understanding of input, lists, string slicing, `for` loops, and list length.

### 🧩 Task:

1. Ask the user to enter their name.
2. Convert the name to a list of characters.
3. Print each character **on a new line** using a `for` loop.
4. Then print:

   * The first 3 letters
   * The last 2 letters
   * The total number of letters using `len()`

---

### 🔍 Sample Output (for `Jahanzaib`)

```
J  
a  
h  
a  
n  
z  
a  
i  
b  

First 3 letters: ['J', 'a', 'h']  
Last 2 letters: ['i', 'b']  
Total letters: 9  
```

---

✅ *End of Assignment*
---

## 📤 Assignment Submission Guidelines

Please follow these instructions carefully to submit your assignment:

1. ✅ **Complete All Questions**
   Make sure you attempt **all questions** from Q1 to the Mini Challenge.

2. 💻 **Run Each Code Cell**
   Ensure that each code block is executed and displays the correct output.

3. 📝 **Use Meaningful Inputs**
   When prompted for input (e.g., name, movie, numbers), use realistic and clear values.

4. 🚫 **Avoid Advanced Topics**
   Do **not** use:

   * `if`, `else`, or any conditional logic
   * `while` loops
   * Functions or libraries not taught yet

   Only use the topics covered in Chapters 2–4:

   * `print()`, `input()`
   * Variables, strings, lists
   * `for` loops, `range()`
   * Type casting (`int()`, `float()`)

5. 📁 **Save and Share Google Coolab Link**
6. 📩 **Submit to Google Classroom**


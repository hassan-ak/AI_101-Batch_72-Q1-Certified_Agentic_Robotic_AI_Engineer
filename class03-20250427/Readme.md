# Class 03 - 2024/04/27 - Batch 72 - Q1 (Certified Agentic Robotic AI Engineer)

**Table of Content**
- [Class 03 - 2024/04/27 - Batch 72 - Q1 (Certified Agentic Robotic AI Engineer)](#class-03---20240427---batch-72---q1-certified-agentic-robotic-ai-engineer)
  - [📘 Chapter 2: **Variables and Simple Data Types**](#-chapter-2-variables-and-simple-data-types)
    - [Key Topics:](#key-topics)
  - [📘 Chapter 3: **Introducing Lists**](#-chapter-3-introducing-lists)
    - [Key Topics:](#key-topics-1)


## 📘 Chapter 2: **Variables and Simple Data Types**

### Key Topics:
- **What happens when you run a Python file**:  
  Python interprets each line, highlights keywords (like `print`), and recognizes strings in quotes.

- **Variables**:
  - Variables are *labels* (not boxes) for values.
  - Example:
    ```python
    message = "Hello Python world!"
    print(message)
    ```

- **Strings**:
  - Text enclosed in quotes (`'...'` or `"..."`).
  - Useful string methods:
    - `.title()` → Capitalizes each word.
    - `.upper()` → Converts to uppercase.
    - `.lower()` → Converts to lowercase.

- **String formatting**:
  - You can insert variables into strings using `f-strings`:
    ```python
    name = "ada lovelace"
    print(f"Hello, {name.title()}!")
    ```

- **Whitespace management**:
  - `\t` for tabs, `\n` for new lines.
  - `.strip()`, `.lstrip()`, `.rstrip()` remove unwanted spaces.

- **Numbers**:
  - **Integers**: Whole numbers (`1`, `-3`, `42`).
  - **Floats**: Numbers with decimals (`3.14`, `0.5`).
  - Mathematical operations: `+`, `-`, `*`, `/`, `**` (exponentiation).

- **Comments**:
  - Use `#` to add comments explaining code.
  
- **The Zen of Python**:
  - Import with `import this` to see guiding principles like:
    - "Simple is better than complex."
    - "Readability counts."

## 📘 Chapter 3: **Introducing Lists**

### Key Topics:
- **What is a List?**
  - An ordered collection of items.
  - Defined using square brackets `[]`.
    ```python
    bicycles = ['trek', 'cannondale', 'redline', 'specialized']
    ```

- **Accessing Elements**:
  - Access using **index**: `list_name[index]`
  - Indexing starts from **0**, not 1.
    ```python
    print(bicycles[0])  # trek
    print(bicycles[-1]) # specialized (last item)
    ```

- **Modifying, Adding, and Removing Elements**:
  - Modify: `list[0] = 'new_value'`
  - Add at end: `list.append('value')`
  - Insert at position: `list.insert(index, 'value')`
  - Remove:
    - `del list[index]`
    - `list.pop()` (removes last item or specific index)
    - `list.remove('value')` (by value)

- **Organizing a List**:
  - Sort permanently: `list.sort()`
  - Sort temporarily: `sorted(list)`
  - Reverse: `list.reverse()`
  - Find list length: `len(list)`

- **Avoiding Index Errors**:
  - Be careful when accessing elements.
  - Use `-1` for the last element.

---

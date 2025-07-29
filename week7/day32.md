# 📅 Day 31 – July 28, 2025

## 🎯 JavaScript String Methods – Practice Questions

Today, I practiced solving various string manipulation problems using JavaScript. The focus was on using loops, conditional logic, and understanding falsy/truthy values.

---

### 🧪 Q1: Remove Vowels from a String

- Assigned a string value for processing.
- Created an empty output string to store characters.
- Used a `for` loop to iterate through each character in the string.
- Applied an `if` condition to check whether a character is **not** a vowel (`a, e, i, o, u`).
- If the character is **not** a vowel, it is added to the output string.
- The final result was printed to the console.

---

### 🧪 Q2: Toggle Each Character in a String

- Assigned a string with mixed case characters.
- Created an empty string to store the toggled output.
- Used a `for` loop to iterate through the string.
- Inside the loop:
  - If a character was lowercase, converted it to uppercase.
  - If it was uppercase, converted it to lowercase.
- Appended each toggled character to the result string.
- Displayed the final toggled string using `console.log`.

---

### 🧪 Q3: Count Length of String Without Using `.length`

- Assigned a string to a variable.
- Initialized a counter variable to zero.
- Used a `for...of` loop to iterate through each character.
- Incremented the counter for each character.
- Printed the final count (length of the string) without using `.length`.

---

### 🧪 Q4: Check if a Character is an Alphabet

- Created a function that receives a single character input.
- Used `toUpperCase()` and `toLowerCase()` methods to determine if the character is an alphabet.
- If both transformations are different, it is an alphabet.
- Otherwise, it's not an alphabet (likely a digit or special character).
- Returned or logged the result accordingly.

---

### ✅ Concepts Practiced

- `for` and `for...of` loops
- `if` / `else if` conditions
- String methods: `toUpperCase()`, `toLowerCase()`
- Working with characters individually
- Manual counter logic
- Logical thinking for alphabet validation

---

### 💡 Also Learned

#### ✅ Falsy and Truthy Values in JavaScript:

- **Falsy values**:
  - `false`, `0`, `""` (empty string), `null`, `undefined`, `NaN`
- **Truthy values**:
  - Any value **not falsy** (like `"hello"`, `[]`, `{}`, `1`, etc.)

Understanding these helps in better control flow and cleaner conditional checks.

---


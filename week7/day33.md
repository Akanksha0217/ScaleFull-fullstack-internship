### 🗓️ July 30, 2025

#### 🔐 Closures
- A **closure** is a function that "remembers" the variables from its outer scope even after the outer function has finished executing.
- Useful in: data privacy, currying, callbacks.
- Interview Tip: Explain using an example where an inner function accesses a variable declared in the outer function.

#### 🔼 Hoisting (Revised)
- **Hoisting** moves declarations (not initializations) to the top of their scope.
- Variables declared with `var` are hoisted and initialized as `undefined`.
- `let` and `const` are hoisted but not initialized (they remain in **Temporal Dead Zone** until declared).
- Functions are hoisted completely (both declaration and definition), but **function expressions** are not.

#### ❌ Different Types of Errors in JavaScript
- **Syntax Error** – Invalid code structure.
  - E.g. missing `}` or `;`
- **Reference Error** – Using a variable that hasn’t been declared.
- **Type Error** – Performing an operation on an incompatible data type.
  - E.g. trying to call a number like a function.
- **Range Error** – A number is outside an allowable range (like recursion limit exceeded).

#### 🧹 Garbage Collection
- JavaScript automatically frees memory when objects are no longer reachable.
- It uses algorithms like **mark-and-sweep**.
- Interview Insight: Explain that you don’t manually manage memory in JS, but writing clean, unreachable-free code helps.

---
Question Practice
- ✅ **Q9: Rotate an array**
  - Shift the last element of the array to the first position.
  - Used array manipulation techniques.

- ✅ **Q10: Function to check Leap Year**
  - Wrote a function that checks leap year logic.
  - Applied conditional checks with `if` statements.

- ✅ **Q11: Addition of Two Arrays**
  - Added elements of two arrays index-by-index.
  - Used loops or array methods to handle array operations.

- ✅ **Q12: Create a Table using JavaScript**
  - Created a dynamic table in HTML.
  - Used DOM methods to:
    - Create elements (`createElement`)
    - Set text or inner HTML
    - Append rows and cells to the table
    - Insert the table into the document

- ✅ **Q13: Find Pairs with Sum 10**
  - Checked all combinations of two numbers in the array.
  - Found and printed the pairs whose sum is 10.

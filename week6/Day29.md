# 📅 Day 29 – July 24, 2025

## 📚 JavaScript Practice – Array Methods & Operators

On this day, I practiced some of the most powerful and commonly used array methods in JavaScript, along with the **spread** and **rest** operators. These are crucial for handling arrays, transforming data, and writing clean and efficient JS code.

---

## ✅ Topics Covered

### 🔁 1. `forEach()`
- Iterates over each element in an array.
- Used to perform side effects like logging or modifying DOM.

```js
const fruits = ['apple', 'banana', 'mango'];
fruits.forEach(fruit => console.log(fruit));
```
### 🔍 2. filter()
- Returns a new array with elements that pass a test function.
```
const numbers = [1, 2, 3, 4, 5];
const even = numbers.filter(num => num % 2 === 0);
console.log(even); // [2, 4]
```

### ➕ 3. reduce()
- rduces the array to a single value (like sum, product, etc.).
```
const nums = [1, 2, 3, 4];
const sum = nums.reduce((acc, curr) => acc + curr, 0);
console.log(sum); // 10
```
### 🌱 4. Spread Operator ...
- Expands elements (used to copy or merge arrays/objects).
```
const arr1 = [1, 2];
const arr2 = [...arr1, 3, 4];
console.log(arr2); // [1, 2, 3, 4]
```
### 📦 5. Rest Operator ...
- Gathers remaining arguments into an array.
```
function total(a, b, ...rest) {
  return a + b + rest.reduce((sum, num) => sum + num, 0);
}
console.log(total(1, 2, 3, 4)); // 10
```

## 📝 Notes
- forEach() doesn’t return anything; it just loops.
- filter() is best when you need to select elements conditionally.
- reduce() is powerful for accumulation tasks (sums, averages, etc.).
- ... spread helps clone arrays or combine them.
- ... rest makes functions flexible to accept many parameters



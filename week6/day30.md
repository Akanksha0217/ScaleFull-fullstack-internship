# 📅 Day 30 – July 25, 2025

## 📘 JavaScript Practice – Arrays, Math Object, Sorting, Loops

Today I practiced array handling, object operations, sorting techniques, and different types of loops in JavaScript.

---

## ✅ Topics Covered

### 🔸 Array of Objects
Storing multiple objects inside a single array.

```js
const users = [
  { name: "Akanksha", age: 22 },
  { name: "Ravi", age: 25 }
];

users.forEach(user => {
  console.log(`${user.name} is ${user.age} years old.`);
});
```
### 🔸 Math Object
- JavaScript built-in Math object provides mathematical functions and constants.
```
console.log(Math.PI);         // 3.141592653589793
console.log(Math.round(4.7)); // 5
console.log(Math.floor(4.9)); // 4
console.log(Math.ceil(4.1));  // 5
console.log(Math.random());   // Random number between 0 and 1
```
### 🔸 sort() Method
- Used for sorting arrays (alphabetical or numeric).
```
const numbers = [5, 2, 9, 1];
numbers.sort((a, b) => a - b); // Ascending sort
console.log(numbers); // [1, 2, 5, 9]
```

### 🔸 for...in Loop
- Used to iterate through object keys.
```
const student = { name: "Akanksha", age: 22, grade: "A" };
for (let key in student) {
  console.log(key + ": " + student[key]);
}
```
### 🔸 for...of Loop
Used to iterate through iterable values like arrays and strings.
```
const fruits = ["apple", "banana", "mango"];
for (let fruit of fruits) {
  console.log(fruit);
}
```

## 📝 Notes
- for...in → loops over keys (best for objects)
- for...of → loops over values (best for arrays, strings)
- Math object → useful for calculations, rounding, random values
- sort() needs a compare function for numeric sorting

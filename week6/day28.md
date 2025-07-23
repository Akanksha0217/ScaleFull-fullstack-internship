# 📅 Day 28 – July 23, 2025

## 🧠 JavaScript Practice – Classes, Objects, Arrays, and Destructuring

---

### 📘 Topics Covered:

- ✅ Creating and using **Classes**
- ✅ Understanding the **`this` keyword**
- ✅ Creating and manipulating **Objects**
- ✅ Working with **Arrays** and common array methods
- ✅ Using **Destructuring** on Arrays and Objects

---
## 🧱 JavaScript Classes

### 👉 What is a Class?
A class is a **template or blueprint** used to create multiple objects with similar properties and methods.

### ✏️ Syntax:
```js

class Student {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }

  showInfo() {
    console.log(`Name: ${this.name}, Age: ${this.age}`);
  }
}
```

### 🔄 this Keyword:
- Refers to the current object instance inside the class.
- Used to access properties or methods of the class.

##  Objects in JavaScript

###🔹 Creating an Object from Class:
```
const s1 = new Student("Akanksha", 20);
s1.showInfo();  // Output: Name: Akanksha, Age: 20
```
### 🔹 Creating an Empty Object:
```
let emptyObj = {};
emptyObj.title = "JavaScript Developer";
```

## 📦 Arrays in JavaScript
 ### 🔹 Creating an Array:
```
let fruits = ["apple", "banana", "mango"];
```
### 🔧 Array Methods:
Method -	Description
length	-Get number of items in array
push()	-Add to the end of the array
pop()	-Remove last element
shift()	-Remove first element
unshift()-	Add element at the beginning
delete- arr[i]	Delete value at index i
slice()	- Extract part of array (non-modify)
splice()	- Add/remove items (modifies array)
toString() -	Convert array to string

## 🧩 What is Destructuring?
Destructuring means breaking apart values from arrays or objects and assigning them to variables in one short line.

 ### ✅ 1. Array Destructuring
 ```
let colors = ["red", "green", "blue"];

let [first, second, third] = colors;

console.log(first);  // red
console.log(second); // green
```

### ✅ 2. Object Destructuring
```
let student = {
  name: "Akanksha",
  roll: 101,
};

let { name, roll } = student;

console.log(name); // Akanksha
console.log(roll); // 101
```
### 🧠 When to Use Destructuring?
- To get values from arrays/objects quickly
- Inside functions, especially with objects
- To write cleaner, shorter code

## 📝 Summary
🔹 Classes make object creation reusable and cleaner.
🔹 Objects store key–value data and behavior (methods).
🔹 Arrays are ordered lists and have many useful built-in methods.
🔹 Destructuring allows for cleaner extraction of values from arrays and objects.

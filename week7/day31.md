# 📅 Day 31 – July 28, 2025

## 🎯 JavaScript String Methods – Practice Questions

Today I practiced some important string manipulation techniques using **JavaScript**, focusing on:

- `for...of` loop  
- `replaceAll()` method  
- `for` loop and `if` condition  
- Working with characters in strings  

---

## 🔍 Questions Solved

### 🧪 Q1: Remove Spaces from a String and Replace with Comma

#### ✅ Method 1: Using `for...of` Loop and `if` Condition
- ✅ Created a function `removeSpacesManual`
- ✅ Initialized an empty string `result`
- ✅ Used `for...of` loop to iterate through the string
- ✅ Checked if character is not a space (`if (char !== " ")`)
- ✅ If true, added character to `result`
- ✅ Printed and returned the final string

#### ✅ Method 2: Using replaceAll() to Replace Space with Comma
- ✅ Created a function removeSpacesWithReplaceAll
- ✅ Used replaceAll(" ", ",") to directly replace all spaces with commas
- ✅ Returned and printed the updated string


### 🧪 Q2: Keep Only Characters (Remove Digits and Special Symbols)

#### ✅ Steps Followed:
- ✅ Created a function  
- ✅ Used `for...of` loop to take each character  
- ✅ Took an empty string `res` to store alphabetic characters  
- ✅ Applied `if` condition using `.toUpperCase()` and `.toLowerCase()` to check if character is a letter  
- ✅ If condition is `true`, added character to result string  
- ✅ Printed final result  
- ✅ Called the function


##📝 Notes
- replaceAll(" ", ",") replaces all whitespaces with commas
- ASCII comparison helps in checking if a character is a letter
- for...of is simple and readable for strings
- Good string cleaning is useful in form validations, text processing


# Programming Hero Batch-12
## Assignment 6 – Questions and Answers
##Name: Dipra Sarker


-----------


Answering the following questions :

### Q1) What is the difference between var, let, and const?

**Answer:**  
The key differences between `var`, `let`, and `const` in JavaScript lie in their **scope, hoisting behavior, and reassignability/redeclaration**:  

- **`var`**: Function-scoped, hoisted with `undefined`, can be re-declared and reassigned.  
- **`let`**: Block-scoped, hoisted but not initialized (temporal dead zone), cannot be re-declared in the same block, but can be reassigned.  
- **`const`**: Block-scoped, hoisted but not initialized, cannot be re-declared or reassigned; objects/arrays can still be modified.  

---

### Q2) What is the difference between map(), forEach(), and filter()?

**Answer:**  
`map()`, `forEach()`, and `filter()` are common array methods with different purposes:

**1. `forEach()`**  
- **Purpose:** Iterate over an array and perform an action on each element.  
- **Return value:** `undefined`.  
- **Mutability:** Can modify external variables; original array unchanged unless explicitly modified.  
- **Use case:** When want to execute a function for each item.  

**2. `map()`**  
- **Purpose:** Create a new array by transforming each element of the original array.  
- **Return value:** New array of same length.  
- **Mutability:** Original array unchanged.  
- **Use case:** When want a new array with modified values.  

**3. `filter()`**  
- **Purpose:** Create a new array containing only elements that satisfy a condition.  
- **Return value:** New array with filtered elements (length may vary).  
- **Mutability:** Original array unchanged.  
- **Use case:** When want to select elements based on a condition.  

**Summary:**  
- Used `forEach()` for side-effects (like printing).  
- Used`map()` to transform elements into a new array.  
- Used `filter()` to pick only the elements that need.  

---

### Q3) What are arrow functions in ES6?

**Answer:**  
Arrow functions are a concise way to write functions in ES6, offering a cleaner syntax than traditional functions and a different behavior for `this`.

**Key Characteristics:**  
1. **Concise syntax:** Single-line functions can omit `{}` and `return`.  
2. **Lexical `this`:** Inherits `this` from the surrounding scope.  
3. **Cannot be used as constructors:** Cannot create objects with `new`.  
4. **No `arguments` object:** Use rest parameters instead.  

**Use case:** Callbacks, array methods (`map`, `filter`, `forEach`), or when `this` should refer to the outer scope.  

---


### Q4) How does destructuring assignment work in ES6?

**Answer:**  
Destructuring assignment allows to **extract values from arrays or objects** into variables quickly and concisely.  

**Types:**  
1. **Array destructuring** – by position.  
2. **Object destructuring** – by property name.  
3. **Nested destructuring** – for nested objects/arrays.  
4. **Function parameter destructuring** – destructure directly in function arguments.  

**Summary:** Destructuring assignment allows to unpack values from arrays or objects into variables quickly and cleanly, reducing repetitive code and improving readability.
      
---


### Q5) Explain template literals in ES6. How are they different from string concatenation?

**Answer:**   Template literals are a way to create strings in ES6 that offer a more flexible and readable syntax than traditional string concatenation. They allow for embedded expressions and multi-line strings, which are not possible with standard strings without special characters.
They are enclosed by backticks (``) instead of single or double quotes. 

**Key Features of Template Literals:**  
1. **Embedded Expressions (String Interpolation):** 
2. **Multi-line Strings:**  

**Difference from String Concatenation:** 

- Template literals solve several problems associated with traditional string concatenation using the plus operator (+).
- Template literals are a superior method for string creation in modern JavaScript, offering a cleaner syntax for variable interpolation, native support for multi-line strings, and the ability to embed any valid JavaScript expression directly within the string.
- Template literals make string creation easier, cleaner, and more readable, especially when combining variables or writing multi-line strings. They replace messy concatenation with a simpler, modern syntax.



## Thank You







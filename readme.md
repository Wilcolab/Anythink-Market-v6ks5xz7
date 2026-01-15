## 📄 Pull Request Description

This PR adds a collection of prompt examples demonstrating different prompting strategies (zero-shot, few-shot, refined, and chain-of-thought style) along with a basic JavaScript implementation. These files were created as part of the quest requirements and are intended to showcase prompt engineering best practices for generating robust string case–conversion functions.

### ✅ What’s Included

* Zero-shot prompt
* Few-shot prompt
* Refined prompt with edge cases
* Chain prompt with sequential steps
* Basic JavaScript implementation

All files follow clear naming conventions and are ready for review.

---

## 📁 Files Added

### 1️⃣ `zero_shot_prompt.txt`

```txt
Write a JavaScript function that converts a given string into kebab-case.
The function should take a single string as input and return the converted string.
```

---

### 2️⃣ `basic_prompt.js`

```javascript
function toKebabCase(str) {
  return str
    .toLowerCase()
    .trim()
    .replace(/\s+/g, "-");
}

// Example usage:
console.log(toKebabCase("Hello World")); // hello-world
```

---

### 3️⃣ `few_shot_prompt.js`

```javascript
/*
Convert strings to kebab-case based on the examples below.

Input: "Hello World"
Output: "hello-world"

Input: "ConvertThisString"
Output: "convert-this-string"

Input: "snake_case_example"
Output: "snake-case-example"

Now write a JavaScript function called toKebabCase that follows these examples.
*/
```

---

### 4️⃣ `refined_prompt.js`

```javascript
/*
Write a robust JavaScript function named toKebabCase that converts strings into kebab-case.

Requirements:
- Handle camelCase, PascalCase, snake_case, and space-separated strings
- Remove or normalize special characters
- Handle edge cases such as empty strings, null, undefined, and non-string inputs
- Include meaningful error handling
- Add comments explaining the logic
- Provide example inputs and outputs
*/
```

---

### 5️⃣ `chain_prompt.js`

```javascript
/*
Step 1: Create a basic JavaScript function named toKebabCase that converts a space-separated string into kebab-case.

Step 2: Enhance the function to support camelCase, PascalCase, snake_case, multiple spaces, and mixed delimiters.

Step 3: Add input validation and error handling for edge cases such as empty strings, null, undefined, numbers, and special characters.
Include comments and example usage.
*/
```

---

## ✅ Checklist

* [x] All required files included
* [x] Clear and readable prompts
* [x] Follows quest instructions
* [x] Ready for review and merge

🚀 **Once this PR is merged, the quest will be fully completed.**
Looking forward to your review!

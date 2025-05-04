# 🔐 Rugged Password Generator App

## 🔗 Live Demo

👉 https://rugged-password-generator.netlify.app/

This is a responsive and powerful **Password Generator App** that I built using vanilla HTML, CSS, and JavaScript. It helps users create strong, customizable passwords with various options like uppercase letters, lowercase letters, numbers, and symbols. It also includes a visual indicator for password strength and a real-time copy-to-clipboard feature.

---

## 📌 Features

- 🎚️ Adjustable password length using a slider
- 🔠 Option to include:
  - Uppercase letters
  - Lowercase letters
  - Numbers
  - Symbols
- 📊 Password strength indicator (Weak, Medium, Strong)
- 📋 Copy password to clipboard with visual feedback
- 🔁 Automatic shuffle of password characters for randomness
- 🔁 Real-time updates as settings are changed

---

## 🧠 Concepts Used

Here are the core concepts and logic I implemented in this project step-by-step:

### 1. **HTML Structure**
   - Clean and semantic markup using `<div>`, `<input>`, `<button>`, etc.
   - `data-` attributes used to reference elements in JavaScript

### 2. **CSS Styling**
   - Responsive design using flexbox
   - Visual strength indicator using background color
   - Style for active copy message animation

### 3. **JavaScript Logic**
   - `querySelector` used to capture and control DOM elements
   - Custom functions to generate:
     - Random Uppercase letters using ASCII (`String.fromCharCode`)
     - Random Lowercase letters using ASCII
     - Random Numbers using `Math.random()`
     - Random Symbols from a predefined string
   - Password length handling with slider and live text
   - Event listeners for checkboxes and buttons
   - Password strength determined by combination of character types and length
   - Password shuffling using **Fisher-Yates Algorithm** for randomness
   - Copy to clipboard with visual message using `navigator.clipboard.writeText`

---

## 📂 Project Folder Structure


---

## 🚀 How to Use

1. Clone or download this repo
2. Open `index.html` in any browser
3. Adjust settings like:
   - Password length (1 to 20)
   - Include uppercase, lowercase, numbers, symbols
4. Click "Generate Password"
5. Use the copy button to copy password to clipboard

---

## 🛠 Tech Stack

- HTML5
- CSS3
- JavaScript (ES6)

---

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/06560528-aab6-44ee-a132-df85a5e6577e)


---

## 🔗 Project Link

- Live Site: https://rugged-password-generator.netlify.app/

---

## 🙋‍♂️ Author

Made with 💻 by Akhilesh PAndey @Emptyskull7

---


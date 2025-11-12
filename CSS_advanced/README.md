# 🎨 Advanced CSS Project

## 🧠 Description

This project focuses on mastering **Advanced CSS concepts**.
You will explore the foundations of modern CSS, including layout systems, variables, animations, transformations, and cross-browser consistency.
The goal is to gain the knowledge necessary to build visually appealing, responsive, and efficient web pages.

---

## 📚 Resources

Before starting, make sure to read or explore the following resources:

- [CSS Reference - A free visual guide to CSS](https://cssreference.io/)
- [Can I use... (Browser compatibility tables)](https://caniuse.com/)
- [CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
- [CSS Properties | HTML Dog](https://htmldog.com/references/css/properties/)
- [Box Sizing](https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing)
- [CSS Specificity](https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity)
- [CSS Specificity Calculator](https://specificity.keegan.st/)
- [Play with CSS Selectors](https://flukeout.github.io/)

---

## 🎯 Learning Objectives

By the end of this project, you should be able to explain (without using Google):

### General
- What are **selectors**, **properties**, and **values**
- The difference between **block** and **inline** styling
- How to ensure **consistency across browsers** (CSS reset)
- How to set up and use **CSS variables**
- The differences between **inline**, **embedded**, and **external CSS**
- How **grid systems** work (especially with floats)
- The difference between **icon webfonts** and **SVG icons**
- The difference between **pseudo-classes** and **pseudo-elements**
- How to create **background gradients**
- How to **animate elements** with CSS
- How to **transform elements** in 2D and 3D
- What **vendor prefixes** are and why they are used

---

## 🧩 Requirements

### General
- **Allowed editors:** vi, vim, emacs, VSCode, Atom
- All files will be interpreted on **Chrome (version 78.x or later)**
- Each file must end with a **new line**
- Each file must start with a **comment describing the task**
- A **README.md** file is **mandatory** at the root of the project
- Code must be **W3C compliant** and pass validation using the **W3C Validator**

---

## 🧠 Key Concepts

### 🧩 CSS Selectors
Selectors are patterns used to target specific elements in an HTML document. You can use **class selectors**, **ID selectors**, **attribute selectors**, or even **pseudo-classes** for dynamic behavior.

### 📦 Box Model & Sizing
Understanding the **box model** (content, padding, border, margin) is essential.
Use `box-sizing: border-box;` to simplify element sizing calculations.

### 🎛 CSS Variables
CSS variables allow for **consistent theming** and easy maintenance:
```css
:root {
  --main-color: #4caf50;
  --font-size: 16px;
}

body {
  color: var(--main-color);
  font-size: var(--font-size);
}
```

### 🎨 Gradients & Animations
Use CSS to create smooth background transitions and animations:
```css
button {
  background: linear-gradient(90deg, #ff7e5f, #feb47b);
  transition: transform 0.3s ease-in-out;
}

button:hover {
  transform: scale(1.1);
}
```

### 💫 Pseudo-Classes vs Pseudo-Elements
- **Pseudo-classes**: represent a state of an element (e.g. `:hover`, `:focus`)
- **Pseudo-elements**: represent part of an element (e.g. `::before`, `::after`)

---

## ✅ Validation

To ensure code quality and compliance, validate your CSS files using the **[W3C CSS Validator](https://jigsaw.w3.org/css-validator/)**.

---

## 🧾 Best Practices

- Always begin each file with a **descriptive comment**
- Use **external CSS** files for better maintainability
- Keep styles **modular and reusable**
- Prefer **CSS variables** over hardcoded values
- Use **responsive units** (%, rem, vw, vh) instead of fixed px
- Regularly validate your CSS with W3C tools
- Check **browser compatibility** on [Can I use...](https://caniuse.com/)

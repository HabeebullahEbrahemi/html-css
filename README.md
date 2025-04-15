# Day 11 – CSS Selectors and Properties

This repository contains learning materials and examples for **Day 11** of the HTML & CSS course, 
focusing on CSS **selectors**, **properties**, and their usage with **classes**, **IDs**, and **attribute selectors**.

---

## 📘 Topics Covered

- What are CSS Selectors?
- Types of Selectors:
  - Universal Selector (`*`)
  - Type Selector (`p`, `h1`, etc.)
  - Class Selector (`.classname`)
  - ID Selector (`#id`)
  - Attribute Selector (`[type="text"]`, `[target="_blank"]`)
- Common CSS Properties:
  - `color`, `background`, `font-size`, `margin`, `padding`, `border`, `text-align`
- Practical Example combining all selector types

---

## 💡 Code Sample

```css
/* Class selector */
.highlight {
  color: white;
  background-color: green;
  padding: 10px;
}

/* ID selector */
#main-heading {
  font-size: 32px;
  color: navy;
}

/* Attribute selector */
a[target="_blank"] {
  color: red;
}

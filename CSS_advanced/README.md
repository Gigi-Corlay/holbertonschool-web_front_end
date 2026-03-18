# 📄 CSS Project – My CSS Learning Project

## 1. Project Overview

This project demonstrates my understanding of **Cascading Style Sheets (CSS)** and how to style HTML content.  
It covers:

- Selectors, properties, and values  
- Box model (margin, padding, border)  
- Inline, embedded, and external CSS  
- Block vs inline elements  
- Flexbox and grid layouts  
- CSS variables  
- Pseudo-classes and pseudo-elements  
- Animations and transforms  
- Backgrounds and gradients  
- Vendor prefixes for browser compatibility  

The goal is to **apply CSS best practices** and make web pages visually appealing and responsive.

---

## 2. Features Implemented

- Responsive navigation bar  
- Flexbox and grid layouts for content sections  
- Styled headings, paragraphs, and lists  
- Animated buttons and hover effects  
- Gradient backgrounds and colored sections  
- SVG icons and web font icons integration  
- Use of pseudo-elements (`::before`, `::after`)  
- CSS variables for color and spacing consistency  

---

## 3. Project Structure
my-css-project/
├── index.html # Main HTML file
├── style.css # External CSS file
├── reset.css # CSS reset file
├── images/ # Image and SVG assets
└── README.md # Project documentation


---

## 4. Key Concepts Learned

### Selectors
```css
p { color: blue; }           /* Type selector */
#header { background: red; } /* ID selector */
.nav { font-size: 16px; }    /* Class selector */
```

## Box Model

- Margin: space outside an element
- Padding: space inside an element
- Border: element border thickness

```css
div {
  margin: 10px;
  padding: 20px;
  border: 2px solid black;
  box-sizing: border-box;
}
.nav { font-size: 16px; }    /* Class selector */
```
CSS Variables
:root {
  --primary-color: #3498db;
}

h1 {
  color: var(--primary-color);
}
Pseudo-classes and Pseudo-elements
a:hover { color: red; }           /* pseudo-class */
p::first-letter { font-size: 2em; } /* pseudo-element */
Animations & Transforms
button {
  transition: background 0.3s;
}

.box:hover {
  transform: scale(1.1);
}
Vendor Prefixes
.box {
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  transform: rotate(45deg);
}

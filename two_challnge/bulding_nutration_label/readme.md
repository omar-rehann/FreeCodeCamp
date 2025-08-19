# Nutrition Facts Label

A pixel-perfect HTML/CSS recreation of an FDA-standard nutrition label, created as part of the freeCodeCamp curriculum to master precision web design.

![Nutrition Label Preview](./preview.png) <!-- Add an actual screenshot later -->

## Project Overview

This project replicates the exact structure and typography of US nutrition labels with:

- 100% accurate spacing and alignment
- FDA-compliant hierarchy
- Responsive typography system
- Print-perfect layout

## Features

### Structural Components
- **Header Section**:
  - Bold "Nutrition Facts" title
  - Serving size information
- **Calories Display**:
  - Large, prominent calorie count (230)
  - "Amount per serving" subheader
- **Nutrient Breakdown**:
  - Macronutrients (Fat, Carbs, Protein)
  - Micronutrients (Vitamins, Minerals)
  - % Daily Values with right alignment
- **Footnote**:
  - Daily value explanation text
  - Fine print styling

### Technical Implementation
- **Typography**:
  - Open Sans (400, 700, 800 weights)
  - Relative units (rem/em) for scalability
  - Precise letter-spacing (0.15px)
- **Layout System**:
  - Flexbox for text alignment
  - Custom divider system (thin, medium, thick)
  - Indentation classes (1em, 2em)
- **Visual Details**:
  - Black containment border
  - Perfect vertical rhythm
  - Right-aligned percentages
  - Nested item styling

## HTML/CSS Techniques

```html
<!-- Semantic structure example -->
<div class="daily-value small-text">
  <p class="bold right no-divider">% Daily Value *</p>
  <div class="divider"></div>
  <p><span><span class="bold">Total Fat</span> 8g</span> <span class="bold">10%</span></p>
</div>
## 🚀 How to Run  
1. Clone or download the repository  
2. Open `index.html` in your browser  
3. Enjoy the CSS-rendered cat illustration

---
## 🌐 Live Preview  
You can preview the documentation page by opening `index.html` locally or hosting it on GitHub Pages.

---

## 📌 Author  
**Omar** – Front-End Developer & CSS Artist  
عمر – مطور واجهات أمامية وفنان CSS

---

## 📢 License  
This project is for educational and artistic purposes, inspired by freeCodeCamp’s CSS art challenges.
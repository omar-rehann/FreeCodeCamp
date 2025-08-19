# Registration Form

A responsive, accessible web form built as part of the freeCodeCamp curriculum to practice HTML forms and CSS styling.

## Project Overview

This project demonstrates:
- Proper HTML form structure and semantics
- Client-side form validation
- Accessible form design
- CSS styling for forms
- Responsive layout techniques

## Key Features

### Form Fields
- **Personal Information**:
  - First name (text, required)
  - Last name (text, required)
  - Email (email validation, required)
  - Password (pattern validation, min 8 chars)
- **Account Type**:
  - Personal/Business (radio buttons)
- **Additional Information**:
  - Profile picture upload
  - Age (number with min/max)
  - Referral source (dropdown)
  - Bio (textarea)
- **Terms Acceptance**:
  - Required checkbox with link to terms

### Technical Features
- Semantic HTML5 form elements
- Client-side validation:
  - Required fields
  - Email format validation
  - Password pattern matching (`[a-z0-5]{8,}`)
  - Age range restriction (13-120)
- Responsive design:
  - Flexible width (60vw) with min/max constraints
  - Mobile-friendly layout
- Accessible:
  - Proper label associations
  - Fieldset/legend for radio groups
  - Sufficient color contrast

## Technologies Used

- HTML5:
  - Form elements (`input`, `select`, `textarea`)
  - Validation attributes (`required`, `pattern`, `min`, `max`)
  - Semantic structure (`fieldset`, `legend`)
- CSS3:
  - Responsive units (vw, em)
  - Attribute selectors
  - Pseudo-classes
  - Flexible box model

## CSS Techniques Demonstrated

```css
/* Key techniques include: */
input[type="submit"] { /* Attribute selector */
  width: 60%;
  min-width: 300px; /* Responsive constraints */
}

.inline {
  width: unset; /* Resetting width */
}

fieldset:last-of-type { /* Structural pseudo-class */
  border-bottom: none;
}
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
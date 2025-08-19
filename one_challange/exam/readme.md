# freeCodeCamp Survey Form

A responsive and accessible survey form built as part of the freeCodeCamp curriculum, showcasing advanced form design techniques and user experience best practices.

## Project Overview

This project demonstrates:
- Comprehensive survey form structure
- Multiple input types and form controls
- Accessible form design principles
- Responsive layout with modern CSS
- Client-side validation

## Key Features

### Form Fields & Controls
- **Personal Information**:
  - Name (text, required)
  - Email (email validation, required)
  - Age (optional number input with min/max)
- **Role Selection**:
  - Dropdown with 5 options
- **Recommendation**:
  - Radio button group (3 options)
- **Improvement Suggestions**:
  - Checkbox group with 11 options
- **Comments**:
  - Textarea for free-form feedback
- **Submission**:
  - Prominent submit button with hover effect

### Technical Highlights
- **Semantic HTML**:
  - Proper use of `fieldset` and `legend`
  - Accessible label associations
- **Responsive Design**:
  - Flexbox layout
  - Percentage-based widths with max-width constraints
  - Mobile-friendly spacing
- **Visual Design**:
  - Dark theme with good contrast
  - Consistent input styling
  - Smooth hover transitions
  - Custom placeholder styling
- **Validation**:
  - Client-side validation for required fields
  - Email format validation
  - Number range constraints

## Technologies Used

- HTML5:
  - Form elements (text, email, number, select, textarea)
  - Radio buttons and checkboxes
  - Semantic structure
- CSS3:
  - Flexbox layout
  - Responsive units (em, %)
  - Box model properties
  - Pseudo-classes (:hover)
  - Custom properties
  - Box shadows

## CSS Techniques Demonstrated

```css
/* Key techniques include: */
.inline {
  width: unset; /* Override default input width */
  vertical-align: middle; /* Align with text */
}

#survey-form {
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* Subtle shadow */
  border-radius: 8px; /* Rounded corners */
}

button#submit {
  transition: background-color 0.3s ease; /* Smooth hover effect */
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
# Rothko-Style CSS Painting

A pure CSS implementation of a Mark Rothko-inspired abstract painting, created as part of the freeCodeCamp curriculum to master advanced CSS techniques.

## Project Overview

This artistic project recreates the essence of Rothko's color field paintings using only HTML and CSS, demonstrating how web technologies can be used for digital art.

## Features

### Visual Composition
- **Layered Color Fields**: Three distinct rectangular forms
- **Frame Treatment**: 50px black border simulating gallery presentation
- **Color Palette**:
  - Background: Deep maroon (#4d0f00)
  - Primary elements: Mustard (#efb762), Crimson (#8f0401), Vermilion (#b20403)

### Technical Implementation
- **CSS Box Model**: Precise dimensional control
- **Transformations**: Subtle rotational offsets (-0.6° to 0.4°)
- **Edge Treatments**:
  - Variable border-radius (8px to 60px)
  - Soft blur filters (1px-2px)
  - Glow effects via box-shadow
- **Layout**:
  - Centered composition
  - Margin auto positioning
  - Overflow containment

## CSS Techniques Demonstrated

```css
/* Color field with asymmetric rounding */
.three {
  border-radius: 30px 25px 60px 12px;
  filter: blur(2px);
}

/* Interactive shadow effect */
.two {
  box-shadow: 0 0 3px 3px #8f0401;
}

/* Subtle angular displacement */
.one {
  transform: rotate(-0.6deg);
}
## 🌐 Live Preview  
You can preview the documentation page by opening `index.html` locally or hosting it on GitHub Pages.

---
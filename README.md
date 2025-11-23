# Lab Assignment 3 - Portfolio Website

Responsive portfolio website using Flexbox, CSS Grid, animations, and media queries

## Description

This project is a modern, responsive portfolio website built as part of Lab Assignment 3. It showcases my skills, projects, and contact information using advanced CSS techniques including Flexbox, CSS Grid, animations, and responsive design.

## Features

- **Flexbox Layout**: Used for navigation, hero section, and flexible content alignment
- **CSS Grid**: Implemented for Skills and Projects sections with responsive grid layouts
- **Responsive Design**: Mobile-first approach with media queries for tablet (768px) and mobile (480px) breakpoints
- **CSS Animations**: 
  - Color-changing effect on name highlight
  - Floating animation on profile circle
  - Fade-in animations for skill cards
  - Smooth transitions on hover effects
- **Interactive Elements**:
  - Hover effects on navigation links
  - Transform effects on buttons and cards
  - Smooth transitions throughout
- **Relative Units**: Uses rem, em, %, vw, vh, and clamp() for scalable design

## Technologies Used

- HTML5
- CSS3
- Google Fonts (Poppins)
- Flexbox
- CSS Grid
- CSS Animations and Transitions
- Media Queries

## File Structure

```
Lab-Assignment-3-Portfolio/
├── index.html       # Main HTML file with portfolio structure
├── style.css        # Complete CSS with Flexbox, Grid, animations
└── README.md        # Project documentation
```

## Responsive Behavior

### Desktop (>768px)
- Full navigation with horizontal links
- Hero section with side-by-side content and image
- Skills and Projects in multi-column grid layout

### Tablet (<=768px)
- Stacked navigation
- Hero content and image stacked vertically
- Skills and Projects adapt to single column

### Mobile (<=480px)
- Optimized padding and spacing
- Smaller profile circle
- Touch-friendly button sizes

## CSS Techniques Implemented

### Flexbox Usage
- Navigation bar (`.nav`)
- Hero section (`.hero`)
- Social links in footer
- Contact form layout

### CSS Grid Usage
- Skills grid (`.skills-grid`) with `repeat(auto-fit, minmax(250px, 1fr))`
- Projects grid (`.projects-grid`) with `repeat(auto-fit, minmax(280px, 1fr))`

### Animations & Transitions
- `@keyframes colorChange` - Hue rotation on name highlight
- `@keyframes float` - Floating profile circle
- `@keyframes fadeInLeft` - Hero content entrance
- `@keyframes fadeIn` - Skill cards entrance
- Hover transitions on all interactive elements

### Responsive Units
- `clamp()` for fluid typography
- `rem` for consistent spacing
- `vw/vh` for viewport-relative sizing
- `%` for flexible layouts

## How to View

1. Clone the repository:
```bash
git clone https://github.com/Amarsh-Dubey/Lab-Assignment-3-Portfolio.git
```

2. Open `index.html` in your web browser

3. Test responsive behavior:
   - Resize browser window
   - Use browser DevTools (F12) to test different device sizes
   - Recommended breakpoints: Desktop (1200px), Tablet (768px), Mobile (480px)

## Live Demo

View the live website at: [GitHub Pages Link](#)

## Learning Outcomes Achieved

✅ Applied Flexbox for alignment and spacing
✅ Implemented CSS Grid for structured layouts
✅ Created responsive design with media queries
✅ Used relative units (rem, em, %, vw, vh)
✅ Added hover effects and transitions
✅ Implemented keyframe animations
✅ Applied CSS transforms on interactive elements
✅ Improved visual hierarchy and design consistency
✅ Combined multiple CSS techniques in one project
✅ Built a polished, professional portfolio

## Author

**Amarsh Dubey**
- GitHub: [@Amarsh-Dubey](https://github.com/Amarsh-Dubey)
- LinkedIn: [Amarsh Dubey](https://www.linkedin.com/in/amarsh-dubey-b56920353a)
- Email: nimeparadise@gmail.com

## Acknowledgments

- Lab Assignment 3 - Web Development Course
- Google Fonts for Poppins font family
- Modern CSS techniques and best practices

---

**Submission Date**: November 2025  
**Course**: Web Development Lab  
**Assignment**: Lab Assignment 3 - Responsive Portfolio Website

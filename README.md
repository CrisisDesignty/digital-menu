# Digital Menu

A modern, responsive single-page restaurant menu website with smooth scrolling and elegant animations.

## Overview

**Project Type**: Single-page restaurant menu website  
**Tech Stack**: Pure HTML/CSS/JavaScript (no frameworks)  
**Total Lines**: ~620 lines of code

## Project Structure

```
digital-menu/
├── index.html          # Main application (244 lines)
├── styles.css          # Complete styling (376 lines)
├── .gitignore          # Git ignore file
└── README.md           # Project documentation
```

## Features

### Navigation System
- **Desktop**: Fixed header with hover dropdown menus organized by category
- **Mobile**: Responsive hamburger menu with smooth slide-in navigation
- **Brand**: "Culinary" restaurant branding

### Menu Display
- **Layout**: 7 full-screen sections with parallax background images
- **Content**: Each dish includes category, name, description, price, and calorie information
- **Transitions**: Enhanced smooth scrolling with custom cubic-bezier easing

### Menu Items

#### Appetizers
- **Bruschetta** - $8.99 (180 cal)
- **Calamari** - $12.99 (320 cal) 
- **Wings** - $10.99 (480 cal)

#### Main Courses
- **Carbonara** - $16.99 (620 cal)
- **Ribeye** - $28.99 (850 cal)
- **Salmon** - $22.99 (540 cal)

#### Desserts
- **Tiramisu** - $7.99 (380 cal)

## Technical Features

### Responsive Design
- **Breakpoints**: 768px and 480px for optimal mobile experience
- **Background**: Parallax effects with fixed attachment (disabled on mobile for performance)
- **Typography**: Scalable fonts and spacing across all devices

### Animation & Interactions
- **Scroll**: Custom smooth scrolling with easeInOutCubic timing function
- **Transitions**: 1.2-second duration for natural movement
- **Section Visibility**: Intersection Observer API for automatic section detection
- **Content Animation**: Fade-in and scale effects for dish content

### Performance
- **Dependencies**: Zero external frameworks or libraries
- **Images**: Optimized Unsplash images with proper sizing
- **CSS**: Efficient use of `will-change` property for smooth animations
- **JavaScript**: Vanilla JS with `requestAnimationFrame` for smooth scrolling

## Browser Support

- Modern browsers with ES6+ support
- CSS Grid and Flexbox compatibility
- Intersection Observer API support

## Usage

Simply open `index.html` in a web browser. No build process or server required.

## Development

The project uses vanilla web technologies:
- **HTML5** for semantic structure
- **CSS3** with modern features (Grid, Flexbox, Custom Properties)
- **JavaScript ES6+** for interactive functionality

No package manager or build tools required for development or deployment.
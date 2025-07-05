# Sarika Kanetkar Portfolio Website

## Overview

This is a personal portfolio website for Sarika Kanetkar, a UI/UX Designer. The project is built as a static website using vanilla HTML, CSS, and JavaScript, focusing on showcasing design work, skills, and professional experience through a clean, modern interface.

## System Architecture

The application follows a simple client-side architecture:

- **Frontend**: Static HTML/CSS/JavaScript website
- **No Backend**: Pure client-side application with no server-side processing
- **No Database**: All content is embedded directly in the HTML
- **Hosting**: Designed for static hosting platforms (GitHub Pages, Netlify, Vercel, etc.)

## Key Components

### 1. HTML Structure (index.html)
- **Navigation**: Fixed header with responsive hamburger menu
- **Sections**: Multi-section single-page application (SPA) layout
  - Home/Hero section
  - About section
  - Projects section
  - Resume section
  - Skills section
  - Contact section

### 2. Styling (styles.css)
- **CSS Variables**: Centralized color scheme and theming system
- **Typography**: Inter font family from Google Fonts
- **Icons**: Font Awesome for iconography
- **Responsive Design**: Mobile-first approach with breakpoints
- **Color Palette**:
  - Primary: Turquoise (#20b2aa)
  - Secondary: Black (#000000)
  - Accent: White (#ffffff)

### 3. Interactive Features (script.js)
- **Mobile Navigation**: Hamburger menu toggle functionality
- **Smooth Scrolling**: Enhanced navigation between sections
- **Scroll Effects**: Dynamic navbar styling based on scroll position
- **Active Link Highlighting**: Navigation state management

## Data Flow

Since this is a static website, data flow is minimal:

1. **User Interaction**: Click events and scroll events captured by JavaScript
2. **DOM Manipulation**: JavaScript updates classes and styles for interactive features
3. **Navigation**: Smooth scrolling between sections using anchor links
4. **Responsive Behavior**: CSS media queries handle layout changes

## External Dependencies

### CDN Resources
- **Google Fonts**: Inter font family for typography
- **Font Awesome 6.0**: Icon library for UI elements

### No Third-party Services
- No analytics tracking
- No form processing services
- No content management systems
- No external APIs

## Deployment Strategy

The application is designed for static hosting with the following characteristics:

- **No Build Process**: Direct deployment of source files
- **No Server Requirements**: Can be served from any static file server
- **Recommended Platforms**:
  - GitHub Pages
  - Netlify
  - Vercel
  - AWS S3 + CloudFront

### Performance Considerations
- Optimized CSS with variables for consistency
- Minimal JavaScript for core functionality
- External fonts and icons loaded from CDN
- Single HTML file for fast initial load

## Changelog

```
Changelog:
- June 28, 2025. Initial setup
```

## User Preferences

```
Preferred communication style: Simple, everyday language.
```